# Changelog

本项目的所有重要更改都将记录在此文件中。

## [1.5.0] - TBD

### Changed

- `trailingComma` 配置从 `"none"` 改为 `"es5"`，支持 ES5 标准的尾随逗号

## [1.4.0] - 2023-02-07

### Changed

- `printWidth` 从 `80` 改为 `100`，增加每行最大字符数

## [1.3.0] - 2022-11-14

### Changed

- YAML/YML/TOML 文件使用双引号（`singleQuote: false`）
- Markdown 文件使用单引号（`singleQuote: true`）

## [1.2.2] - 2022-11-11

### Added

- 新增 YAML/YML/TOML 文件类型的覆盖配置

## [1.2.1] - 2022-08-07

### Changed

- 重命名包为 `prettier-config-common`

## [1.2.0] - 2022-07-19

### Added

- 新增 `prettier.all.json` 完整配置文件

## [1.1.2] - 2022-03-30

### Fixed

- 修复配置导出问题

## [1.1.1] - 2022-01-01

### Removed

- 移除已废弃的 `jsxBracketSameLine` 配置项，改用 `bracketSameLine`

## [1.0.4] - 2021-08-26

### Fixed

- 修复配置问题

## [1.0.3] - 2021-01-23

### Added

- 新增功能支持

## [1.0.2] - 2019-05-03

### Fixed

- 修复配置问题

## [1.0.1] - 2019-04-30

### Fixed

- 修复初始版本问题

## [1.0.0] - 2019-04-16

### Added

- 初始版本发布
- 基础 prettier 配置
- 支持 JSON5 文件覆盖配置
- 支持 `.prettierrc` 文件解析器配置

### 配置项默认值

| 配置项 | 值 |
| --- | --- |
| printWidth | `80` |
| tabWidth | `4` |
| useTabs | `true` |
| semi | `false` |
| singleQuote | `true` |
| jsxSingleQuote | `false` |
| trailingComma | `"none"` |
| bracketSpacing | `true` |
| bracketSameLine | `false` |
| arrowParens | `"avoid"` |
| endOfLine | `"auto"` |
