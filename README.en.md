# @saqqdy/prettier-config

### Description
个人自用的prettier配置

### Software Architecture
请在使用前确保您本地开启了prettier

### Installation

```
# 使用npm安装
npm install @saqqdy/prettier-config -D
# 使用yarn安装
yarn add @saqqdy/prettier-config --dev
```

### Instructions

#### 方法1. 修改package.json

```
# 编辑您项目package.json加上下面这一行
{
  ...
  "prettier": "@saqqdy/prettier-config",
  ...
}
```

#### 方法2. 创建/修改本地.prettierrc.js文件

```
# 编辑.prettierrc.js
module.exports = {
  ...require("@saqqdy/prettier-config"),
  semi: false
}
```

### Contribution

1. Fork the repository
2. Create Feat_xxx branch
3. Commit your code
4. Create Pull Request


### About Me

1. You can use Readme\_XXX.md to support different languages, such as Readme\_en.md, Readme\_zh.md
2. My Gitee：[https://gitee.com/saqqdy](https://gitee.com/saqqdy)
3. My Github：[https://github.com/saqqdy](https://github.com/saqqdy)
4. My npm：[https://npmjs.com/~saqqdy](https://npmjs.com/~saqqdy)
5. My porsonal site [http://www.saqqdy.com](http://www.saqqdy.com)


