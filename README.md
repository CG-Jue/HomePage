# Astro 入门套件：基础

```sh
npm create astro@latest -- --template basics
```

[![在 StackBlitz 中打开](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![在 CodeSandbox 中打开](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![在 GitHub Codespaces 中打开](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)


## 🚀 项目结构

在你的 Astro 项目中，你会看到以下文件夹和文件：

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

要了解有关 Astro 项目文件夹结构的更多信息，请参阅[我们的项目结构指南](https://docs.astro.build/zh-cn/basics/project-structure/)。

## 🧞 命令

所有命令都从项目的根目录在终端中运行：

| 命令                     | 操作                                             |
| :---------------------- | :----------------------------------------------- |
| `npm install`           | 安装依赖                                          |
| `npm run dev`           | 在 `localhost:4321` 启动本地开发服务器            |
| `npm run build`         | 构建你的生产站点到 `./dist/`                      |
| `npm run preview`       | 在部署前本地预览你的构建                          |
| `npm run astro ...`     | 运行 CLI 命令，如 `astro add`、`astro check`      |
| `npm run astro -- --help` | 获取使用 Astro CLI 的帮助                       |

## 👀 想了解更多？

随时查看[我们的文档](https://docs.astro.build/zh-cn)或加入我们的[Discord 服务器](https://astro.build/chat)。
