# @saqqdy/prettier-config

### 介绍
个人自用的prettier配置

### 软件架构
请在使用前确保您本地开启了prettier

### 安装教程

```
# 使用npm安装
npm install @saqqdy/prettier-config -D
# 使用yarn安装
yarn add @saqqdy/prettier-config --dev
```

### 使用说明

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

### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


### 我的相关

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 我的码云：[https://gitee.com/saqqdy](https://gitee.com/saqqdy)
3. 我的Github：[https://github.com/saqqdy](https://github.com/saqqdy)
4. 我的npm：[https://npmjs.com/~saqqdy](https://npmjs.com/~saqqdy)
5. 我的个人网站 [http://www.saqqdy.com](http://www.saqqdy.com)


