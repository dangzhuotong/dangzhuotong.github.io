# dangzhuotong.github.io

卓橦（Zhuo Tong）的个人主页：独立开发者，正在尝试一人团队。这里放作品、工作方式和可以找到我的频道。对外署名「卓橦」。

- 线上地址：https://dangzhuotong.github.io
- 纯静态页面（HTML + CSS + 少量 JS），无构建步骤，由 GitHub Pages 直接从 `master` 分支根目录发布。

## 本地预览

用任意静态服务器在仓库根目录启动即可，例如：

```bash
python3 -m http.server 8000
# 或 npx serve .
```

然后打开 http://localhost:8000 。产品介绍在 `products/<slug>.html`。

## 修改内容

- 页面文字与链接：`index.html`
- 产品文稿：`products/<slug>.md`（中文介绍，不写星数和下载量）
- 产品页面：`products/<slug>.html`
- 样式：`styles.css`
- 交互（主题切换、截图切换、入场动画）：`main.js`
- 图片：`assets/`。站点图标与社交预览来自 [tongyun-scaffold/brand](https://github.com/dangzhuotong/tongyun-scaffold/tree/main/brand)。
