# 钻石比例计算与评级 · 2.0

此文件夹是最新版 2.0 的 GitHub Pages 发布包。

## 文件

- `index.html`：完整网页，已内嵌样式、脚本、参考数据和 SVG，无需安装依赖或构建。
- `.nojekyll`：让 GitHub Pages 直接发布静态文件。
- `README.md`：本说明。

将本文件夹内的文件上传到仓库根目录，确保根目录能直接看到 `index.html`，不要再套一层 `2.0github` 目录。

## GitHub Pages 发布说明

最终交付文件是本目录的 **index.html**，样式、脚本、参考表与矢量图已内嵌。

## 先查看

把 index.html 用浏览器打开即可。文件默认没有测试数值，填入测量数据后自动计算；刷新会清空。

本次已通过本地网页预览验收和单文件依赖检查。自动预览工具禁止 file://，本地双击打开未在工具中实测。

## 发布

1. 使用准备发布的 GitHub 仓库，将这个 **index.html** 放到仓库根目录并提交到发布分支，例如 main。
2. 打开仓库 **Settings → Pages**。
3. 在 **Build and deployment** 中，Source 选择 **Deploy from a branch**。
4. 选择存放文件的分支和 **/(root)**，保存。
5. 等待部署完成，通过 Pages 页面显示的网址访问。

无需上传课程 PDF、原始截图、过程.md、阶段目录或测试截图。只上传最终 index.html 即可。若仓库已有其他内容，也可将文件放到 docs/index.html，并在 Pages 中选择 /docs。

操作依据：[GitHub 官方：配置 Pages 发布来源](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)（2026-10-09 核对）。

本次只完成发布准备，尚未创建或修改远程仓库、开启 Pages 或公开发布。

## 更新网页

以后将更新后的 index.html 替换到同一发布位置并提交，Pages 会按配置重新部署。
