# 个人主页（GitHub Pages）

这是一个可直接部署到 **GitHub Pages** 的个人主页模板（纯 HTML + CSS）。

## 已内置自动部署（推荐）

仓库已包含 `.github/workflows/pages.yml`，推送到 `main` 后会自动部署到 Pages。

1. 进入仓库 **Settings → Pages**
2. 在 **Build and deployment** 中选择 **Source: GitHub Actions**
3. 推送代码到 `main` 分支
4. 等待 Actions 运行完成后访问站点

## 手动分支部署（可选）

如果你不想用 GitHub Actions，也可以用分支部署：

1. 在 **Settings → Pages** 中选择 **Source: Deploy from a branch**
2. Branch 选择 `main`（或默认分支）和 `/ (root)`
3. 保存后等待 1~3 分钟

## 使用步骤

1. 替换 `index.html` 中的个人信息（名字、简介、项目链接、联系方式）。
2. 仓库命名建议：
   - 个人主页：`<你的GitHub用户名>.github.io`
   - 项目主页：任意仓库名（访问地址会是 `https://<用户名>.github.io/<仓库名>/`）

## 本地预览

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。
