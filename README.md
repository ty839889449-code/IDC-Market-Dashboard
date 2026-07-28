# TECNO区域销售市场看板｜GitHub Pages完整版部署包

本包采用与“完整版看板”一致的直接部署结构，全部网页资源与24个市场数据均已内嵌至 `index.html`。

## 文件说明

- `index.html`：完整交互看板，包含国家、品牌与九档价位切换。
- `.nojekyll`：关闭 Jekyll 处理。
- `README.md`：部署说明。

## 部署步骤

1. 在 GitHub 新建一个仓库。
2. 将本包内的 `index.html`、`.nojekyll` 和 `README.md` 上传至仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中，将 **Source** 设置为 **Deploy from a branch**。
5. 选择 `main` 分支和 `/ (root)` 目录，点击 **Save**。
6. 等待 GitHub Pages 完成发布。

发布地址通常为：

`https://你的GitHub用户名.github.io/仓库名/`

## 数据口径

- IDC Sell-in，2026Q1。
- 24个去重市场、9档价位。
- 近24个月连续数据充分的市场采用滚动12个月对比；数据不足的市场使用25Q1与26Q1同比口径，并在页面中明确提示。
- 滚动Sell-in累计仅作为潜在换机池代理，不等同于真实在网存量。
