# 软件操作教程集合

这是一个软件操作教程的静态网站，包含了多个详细的软件使用教程。

## 目录结构

```
.
├── index.html          # 主页
├── 软件操作教程/       # 教程文件目录
└── lib/               # 资源文件目录
    ├── fonts/        # 字体文件
    └── media/        # 媒体文件
```

## 部署说明

这个项目可以直接部署到GitHub Pages上。部署步骤：

1. 在GitHub上创建新的仓库
2. 将所有文件推送到仓库的main分支
3. 在仓库设置中启用GitHub Pages：
   - 进入仓库的Settings标签
   - 找到Pages选项
   - 在Source下选择main分支
   - 点击Save保存设置

部署完成后，网站将通过 `https://[你的用户名].github.io/[仓库名]` 访问。

## 本地预览

你可以通过以下方式在本地预览网站：

1. 使用Python启动一个简单的HTTP服务器：
   ```bash
   python -m http.server 8000
   ```
2. 在浏览器中访问 `http://localhost:8000`

## 更新内容

如需更新内容，直接修改相应的HTML文件即可。修改后推送到GitHub仓库，GitHub Pages会自动更新网站内容。