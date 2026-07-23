# TECNO CAMON 数据看板

这是一个可直接部署到 GitHub Pages 的静态网页版本，包含 25 个市场和 9 档价位的交互分析。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库。
2. 将本目录内的全部文件上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中，将 **Source** 设为 **Deploy from a branch**。
5. 选择 `main` 分支和 `/ (root)` 目录，点击 **Save**。
6. 等待约 1–3 分钟，GitHub 会生成访问地址：

   `https://你的GitHub用户名.github.io/仓库名/`

## 文件说明

- `index.html`：完整交互看板，网站首页。
- `.nojekyll`：关闭 Jekyll 处理，确保静态页面按原结构发布。

## 注意

看板包含 IDC 市场分析数据。若使用公开仓库或公开 GitHub Pages，任何获得链接的人都可以访问。
