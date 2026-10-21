# Stagbar — 品牌站产物（stagbar.vapepl.com）

本目录是 Stagbar 品牌站（Cloudflare Pages 项目 `stagbar-vapepl`）的静态构建产物，由 `bun run build` 生成，**请勿手改**——重新构建会整体重生成。

- 品牌：Stagbar（stagbar.vapepl.com）
- 规模：1 个型号、10 个口味变体页
- 用途：信息/导购站，全部购买 CTA 带 UTM 指向 https://vapepl.com（所有成交在 vapepl.com 完成）
- 部署：`bun run deploy stagbar`（wrangler 直传）或 `bun run package` 出 `dist/stagbar-vapepl.zip` 拖入 CF 控制台上传

关键文件：`CNAME`（CF Pages 自定义域声明，内容为 `stagbar.vapepl.com`）、`sitemap.xml`、`robots.txt`、`llms.txt`、`404.html`。
