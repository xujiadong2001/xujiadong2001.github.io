# Jiadong Xu 的学术主页

线上地址：https://xujiadong2001.github.io/

纯静态 HTML/CSS，无构建依赖。GitHub Pages 从 `master` 分支根目录发布。

## 文件

- `index.html`：个人介绍、研究论文、教育背景、联系信息。
- `assets/home.css`：响应式样式。
- `assets/RealTwin-RL.pdf`：RealTwin-RL 的 8 页匿名投稿论文，供公开下载。
- `assets/favicon.svg`：网站图标。
- `assets/profile.jpeg`：用户提供的个人照片。
- `blog-2021.html`：原博客首页；旧文章、归档及资源保留原路径。

## 本地预览

```sh
python3 -m http.server 8841 --bind 127.0.0.1
```

访问 http://127.0.0.1:8841 。修改后提交并推送到 `master`，GitHub Pages 会自动发布。

## 内容维护

初版依据 2026-10-04 英文 CV，论文外链核对于 2026-10-07。
已录用、预印本和在投论文分别标注；录用状态以 CV 为准。AnchorVLA4D 于 2026-10-07 按用户确认更新为 Submitted to ICRA 2027。AT-VLA 的 arXiv 年份及作者 Guangrui Ren 的拼写使用公开论文信息。

更新论文时编辑 `index.html` 的对应 `article`。替换论文 PDF 时保留文件名以保持链接稳定，并更新页脚与 `sitemap.xml` 中日期。

2026-10-07：按用户要求移除全部 CV 下载入口和线上 CV 文件，新增 RealTwin-RL 论文 PDF 下载。原 CV 已移至本地项目的回收站。
