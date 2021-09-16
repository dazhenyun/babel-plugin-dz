# @dzo/babel-plugin-dz

## 安装
```
npm install @dzo/babel-plugin-dz --save-dev
```
### 使用说明
```
// .babelrc
"plugins": [
    [
      "@dzo/babel-plugin-dz",
      {
        "library": "yournpm" // 支持数组["yournpm", "yournpm2"]
      }
    ],
  ]
  
// index.js
import { helloworld } from 'yournpm';

      ↓ ↓ ↓ ↓ ↓ ↓

var _helloworld = require('yournpm/lib/helloworld');
```


