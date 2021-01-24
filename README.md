## 安装依赖

使用 `yarn install` 来安装依赖能够在 `packages.json` 中存在 `workspaces` 时来创建软链，而直接使用 yarn 是不行的,仅仅只能安装依赖而不能创建 link。

## yarn workspace vs lerna

> 很多功能是重复和相等的

### 侧重点不同:

1. yarn
   重点在于包管理，处理依赖，处理软链
   yarn install = learn bootstrap

   给子项目添加依赖包
   yarn workspace [子项目] add [包]

2. lerna
   重点在于多个项目管理和发布
