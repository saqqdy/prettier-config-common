<div style="text-align: center;" align="center">

# prettier-config-common

适合中国人使用习惯的 prettier 配置

[![NPM version][npm-image]][npm-url]
[![Codacy Badge][codacy-image]][codacy-url]
[![License][license-image]][license-url]

[![Sonar][sonar-image]][sonar-url]

</div>

> 请在使用前确保您本地安装了 prettier

## 安装

```shell
# 使用pnpm安装
pnpm install -D prettier-config-common

# 使用yarn安装
yarn add prettier-config-common --dev

# 使用npm安装
npm install prettier-config-common -D
```

## 使用方法

### 方法 1. 修改 package.json（推荐）

编辑您项目 package.json 加上下面这一行

```json
{
  "prettier": "prettier-config-common"
}
```

### 方法 2. 创建/修改本地 .prettierrc.js 文件

```js
// 编辑 .prettierrc.js
module.exports = require('prettier-config-common')
```

### 方法 3. 使用完整配置

如需使用包含所有配置项的完整版本：

```js
// 编辑 .prettierrc.js
module.exports = require('prettier-config-common/prettier.all.json')
```

## 配置文件说明

本包提供两个配置文件：

| 文件 | 说明 |
| --- | --- |
| `prettier.json` | 精简版配置，仅包含常用配置项（默认） |
| `prettier.all.json` | 完整版配置，包含所有可配置项 |

## 配置详情

### 基础配置

| 配置项 | 值 | 说明 |
| --- | --- | --- |
| printWidth | `100` | 每行最大字符数 |
| tabWidth | `4` | 缩进空格数 |
| useTabs | `true` | 使用 Tab 缩进 |
| semi | `false` | 不使用分号 |
| singleQuote | `true` | 使用单引号 |
| jsxSingleQuote | `false` | JSX 中使用双引号 |
| trailingComma | `"es5"` | 尾随逗号，ES5 标准 |
| bracketSpacing | `true` | 对象字面量大括号内加空格 |
| bracketSameLine | `false` | JSX 标签的 `>` 不单独一行 |
| arrowParens | `"avoid"` | 箭头函数单参数省略括号 |
| endOfLine | `"auto"` | 换行符自动检测 |

### 文件类型覆盖配置

| 文件类型 | 特殊配置 |
| --- | --- |
| `*.json5` | `singleQuote: false`, `quoteProps: "preserve"` |
| `*.yml`, `*.yaml`, `*.toml` | `useTabs: false`, `singleQuote: false`, `tabWidth: 2` |
| `*.md` | `useTabs: false`, `singleQuote: true`, `tabWidth: 2` |
| `.prettierrc` | `parser: "json"` |

## 扩展配置

如需在现有配置基础上进行扩展：

```js
// .prettierrc.js
const baseConfig = require('prettier-config-common')

module.exports = {
  ...baseConfig,
  // 自定义配置覆盖
  printWidth: 120,
  // 添加更多 overrides
  overrides: [
    ...baseConfig.overrides,
    {
      files: '*.vue',
      options: {
        singleQuote: false
      }
    }
  ]
}
```

## 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request

## 相关链接

- 我的码云：[https://gitee.com/saqqdy](https://gitee.com/saqqdy)
- 我的 Github：[https://github.com/saqqdy](https://github.com/saqqdy)
- 我的 npm：[https://npmjs.com/~saqqdy](https://npmjs.com/~saqqdy)
- 我的个人网站：[http://www.saqqdy.com](http://www.saqqdy.com)

## License

[MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/prettier-config-common.svg?style=flat-square
[npm-url]: https://npmjs.org/package/prettier-config-common
[codacy-image]: https://app.codacy.com/project/badge/Grade/f70d4880e4ad4f40aa970eb9ee9d0696
[codacy-url]: https://www.codacy.com/gh/saqqdy/prettier-config-common/dashboard?utm_source=github.com&utm_medium=referral&utm_content=saqqdy/prettier-config-common&utm_campaign=Badge_Grade
[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE
[sonar-image]: https://sonarcloud.io/api/project_badges/quality_gate?project=saqqdy_prettier-config-common
[sonar-url]: https://sonarcloud.io/dashboard?id=saqqdy_prettier-config-common
