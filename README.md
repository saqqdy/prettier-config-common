# prettier-config-common

## 介绍

个人推荐的 prettier 配置

## 软件架构

请在使用前确保您本地开启了 prettier

## 安装教程

```shell
# 使用pnpm安装
pnpm install -D prettier-config-common

# 使用yarn安装
yarn add prettier-config-common --dev

# 使用npm安装
npm install prettier-config-common -D
```

## 使用说明

### 方法 1. 修改 package.json

编辑您项目 package.json 加上下面这一行

```json
{
    "prettier": "prettier-config-common"
}
```

### 方法 2. 创建/修改本地.prettierrc.js 文件

```js
// 编辑.prettierrc.js
module.exports = require('prettier-config-common')
```

## 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request

## 我的相关

1. 使用 Readme_XXX.md 来支持不同的语言，例如 Readme_en.md, Readme_zh.md
2. 我的码云：[https://gitee.com/saqqdy](https://gitee.com/saqqdy)
3. 我的 Github：[https://github.com/saqqdy](https://github.com/saqqdy)
4. 我的 npm：[https://npmjs.com/~saqqdy](https://npmjs.com/~saqqdy)
5. 我的个人网站 [http://www.saqqdy.com](http://www.saqqdy.com)
