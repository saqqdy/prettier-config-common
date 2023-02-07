<div style="text-align: center;" align="center">

# prettier-config-common

适合中国人使用习惯的 prettier 配置

[![NPM version][npm-image]][npm-url]
[![Codacy Badge][codacy-image]][codacy-url]
[![License][license-image]][license-url]

[![Sonar][sonar-image]][sonar-url]

</div>

> 请在使用前确保您本地安装了 prettier

## Installation

```shell
# use pnpm
pnpm install -D prettier-config-common

# use yarn
yarn add prettier-config-common --dev

# use npm
npm install prettier-config-common -D
```

## Instructions

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

## Contribution

1. Fork the repository
2. Create Feat_xxx branch
3. Commit your code
4. Create Pull Request

## About Me

1. You can use Readme_XXX.md to support different languages, such as Readme_en.md, Readme_zh.md
2. My Gitee：[https://gitee.com/saqqdy](https://gitee.com/saqqdy)
3. My Github：[https://github.com/saqqdy](https://github.com/saqqdy)
4. My npm：[https://npmjs.com/~saqqdy](https://npmjs.com/~saqqdy)
5. My porsonal site [http://www.saqqdy.com](http://www.saqqdy.com)

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
