# TECNO Market Opportunity Dashboard — Secure GitHub Pages Package

版本：`8.3.0-secure-qna.1`

本目录可直接部署到 GitHub Pages。`index.html` 使用 StatiCrypt 兼容的浏览器端加密，访问者首先看到问答验证页，答对后才会在本地浏览器中解密完整看板。

## 验证问题

问题：`最好的影像手机品牌是什么？`

答案未写入本部署包。验证区分大小写，请由看板所有者单独告知授权用户。

## GitHub Pages 部署

1. 新建一个没有提交过明文看板的 GitHub 仓库。
2. 将本目录内的全部文件上传到仓库根目录。
3. 进入 `Settings > Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. 选择 `main` 与 `/ (root)`，保存。
6. 打开 GitHub 提供的 `github.io` 地址，检查问答页与解密后的看板。

## 文件

- `index.html`：加密后的完整看板与问答入口。
- `.nojekyll`：阻止 Jekyll 改写静态页面。
- `robots.txt`：请求搜索引擎不要收录。
- `version.json`：版本、来源与校验摘要。
- `SECURITY.md`：部署安全注意事项。

请勿把原始 HTML、IDC 数据文件、答案或解密后的导出文件提交到公开仓库。
