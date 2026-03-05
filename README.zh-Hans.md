# CJK Layout Lab（汉字排版实验室）

[English](./README.md)

## 简介

这是一个基于Astro的排版实验站，优先使用原生Web标准（HTML/CSS）探索CJK排版。

| Demo | 路径 | 说明 |
| :--- | :--- | :--- |
| Writing Modes | `/demos/writing-mode.html` | 对照横排与直排，展示`writing-mode`、`text-orientation`、多栏和首行缩进。 |
| Traditional Book | `/demos/traditional-book.html` | 模拟古籍书页，展示`vertical-rl`、段首缩进与专名号样式。 |
| Chinese Line Breaking | `/demos/zh-line-breaking.html` | 行首行尾禁则。 |
| Symbol of death | `/demos/shiwanghao.html` | 示亡号与†/‡对照。 |

后续将补充Ruby等实验。

## 开发命令

所有命令均在项目根目录执行。

| Command | 说明 |
| :--- | :--- |
| `npm install` | 安装项目依赖。 |
| `npm run dev` | 启动本地开发服务器（`localhost:4321`）。 |
| `npm run build` | 构建生产静态站点到`./dist/`。 |
| `npm run preview` | 本地预览生产构建结果。 |
