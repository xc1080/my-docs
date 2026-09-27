# My Docs

[![MkDocs](https://img.shields.io/badge/MkDocs-Material-526CFE?logo=materialformkdocs&logoColor=white)](https://www.mkdocs.org/)
[![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-222222?logo=github)](https://pages.github.com/)

一个使用 MkDocs Material 构建的轻量技术文档示例，包含首页、指南、API 参考与项目介绍，并通过 GitHub Actions 自动部署。

## 本地预览

```bash
python -m pip install mkdocs-material
mkdocs serve
```

打开 `http://127.0.0.1:8000` 查看实时预览。

## 构建

```bash
mkdocs build
```

生成的静态站点位于 `site/` 目录。

## 目录结构

```text
├── docs/          # Markdown 文档
├── mkdocs.yml     # 站点配置与导航
└── .github/       # 自动部署工作流
```
