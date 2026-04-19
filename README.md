# 个人主页（GitHub Pages）

这是一个可直接部署到 **GitHub Pages** 的个人主页模板（纯 HTML + CSS）。

## 使用步骤

1. 替换 `index.html` 中的个人信息（名字、简介、项目链接、联系方式）。
2. 将仓库名设置为：
   - 个人主页：`<你的GitHub用户名>.github.io`
   - 或项目主页：任意仓库名（需在设置里开启 Pages）。
3. 推送到 GitHub 后，在仓库 **Settings → Pages**：
   - Source 选择 `Deploy from a branch`
   - Branch 选择 `main`（或你的默认分支）和 `/ (root)`
4. 保存后等待 1~3 分钟，即可访问站点。

## 本地预览

可直接双击打开 `index.html`，或使用本地服务器：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。
