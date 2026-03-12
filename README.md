# 学术网站模板（已清理）

这是一个基于 Astro + React 的个人学术网站。

## 当前状态

- 已删除模板自带示例文章、项目和友链。
- 已将主要可视化文案统一为中文。
- 首页、归档、标签、分类、404 等页面均可在空数据下正常显示。

## 常用命令

| Command        | Action                       |
| :------------- | :--------------------------- |
| `pnpm i`       | 安装依赖                     |
| `pnpm dev`     | 本地开发（`localhost:4321`） |
| `pnpm build`   | 构建生产版本到 `./dist/`     |
| `pnpm preview` | 本地预览构建结果             |
| `pnpm lint`    | 使用 Prettier 格式化代码     |

## 内容维护

- 文章目录：`src/content/posts/`
- 项目目录：`src/content/projects/`
- 友链目录：`src/content/friends/`
- 关于页：`src/content/spec/about.md`
- 站点配置：`src/config.json`
