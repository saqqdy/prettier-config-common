<div style="text-align: center;" align="center">

# prettier-config-common

适合中国人使用习惯的 prettier 配置

[![NPM version][npm-image]][npm-url]
[![Codacy Badge][codacy-image]][codacy-url]
[![License][license-image]][license-url]

[![Sonar][sonar-image]][sonar-url]

</div>

> 请在使用前确保您本地安装了 prettier

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

## License

[MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/prettier-config-common.svg?style=flat-square
[npm-url]: https://npmjs.org/package/prettier-config-common
[codacy-image]: https://app.codacy.com/project/badge/Grade/f70d4880e4ad4f40aa970eb9ee9d0696
[codacy-url]: https://www.codacy.com/gh/saqqdy/prettier-config-common/dashboard?utm_source=github.com&utm_medium=referral&utm_content=saqqdy/prettier-config-common&utm_campaign=Badge_Grade
[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE
[sonar-image]: https://sonarcloud.io/api/project_badges/quality_gate?project=saqqdy_eslint-sets
[sonar-url]: https://sonarcloud.io/dashboard?id=saqqdy_eslint-sets
