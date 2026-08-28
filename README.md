# Hugo Blog

这是一个使用 Hugo 构建的个人博客。

## 本地预览

需要安装 Hugo Extended：

```bash
hugo server -D
```

浏览器打开 <http://localhost:1313/>。

## 正式构建

```bash
hugo --gc --minify
```

将仓库推送到 GitHub 后，`.github/workflows/deploy.yml` 会自动部署到 GitHub Pages。

部署前请将 `hugo.toml` 中的 `baseURL` 替换为自己的 GitHub Pages 地址。
