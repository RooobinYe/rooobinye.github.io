# RobinYe's Blog

基于 [Quarto](https://quarto.org/) 构建的个人博客，托管在 GitHub Pages。

## 发表新文章

1. 在 `posts/` 目录下创建新文件夹和 `index.qmd` 文件：

```bash
mkdir posts/my-post-title
```

2. 编辑 `posts/my-post-title/index.qmd`，添加 frontmatter 和正文：

```yaml
---
title: "文章标题"
author: "RobinYe"
date: "YYYY-MM-DD"
categories: [分类1, 分类2]
description: "文章摘要"
---

正文内容...
```

3. 本地预览：

```bash
quarto preview
```

4. 提交并推送到 `main` 分支，GitHub Actions 会自动构建并发布：

```bash
git add .
git commit -m "message"
git push
```
