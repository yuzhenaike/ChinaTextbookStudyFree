# ChinaTextbookStudyFree

一个纯静态的教材学习资源**导航索引**站点，按学段（小学 / 初中 / 高中 / 大学）提供跳转入口，链接到公开开源仓库 [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook) 与[国家中小学智慧教育平台](https://basic.smartedu.cn)。

## 合规与版权说明

- 本仓库**仅包含导航网页**，不存储、不上传、不分发任何教材 PDF 副本。
- 页面中所有外链均指向上述公开来源；教材版权归原出版方所有，资源请仅限个人学习使用。
- 如认为某一导航链接存在版权问题，可联系仓库维护者移除对应链接。

## 本地预览

无需构建工具，直接用浏览器打开 `index.html`，或在本目录运行：

```bash
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 部署（GitHub Pages）

1. 将本目录推送到 GitHub 仓库 `ChinaTextbookStudyFree` 的 `main` 分支。
2. 仓库 **Settings → Pages**，Source 选择 `main` 分支 / 根目录（`/root`）。
3. 发布后访问 `https://<用户名>.github.io/ChinaTextbookStudyFree/`。
