# GitHub Pages 部署说明

## 🚀 自动部署设置

本项目已配置自动部署到GitHub Pages，但需要先手动启用GitHub Pages功能。

### 📋 启用步骤

1. **进入仓库设置**
   - 在GitHub仓库页面，点击 **Settings** 标签

2. **配置Pages**
   - 在左侧菜单中找到 **Pages**
   - 在 **Source** 部分，选择 **GitHub Actions**
   - 点击 **Save** 保存设置

3. **触发部署**
   - 推送代码到 `main` 分支，或
   - 在 **Actions** 标签中手动运行 "Deploy static content to Pages" 工作流

### 🌐 访问网站

配置完成后，网站将在以下地址可用：
```
https://your-username.github.io/web-develop-demo-in-harmony-os-pc/
```

### ⚠️ 注意事项

- 首次配置可能需要几分钟才能生效
- 确保仓库是公开的，或者您有GitHub Pro账户（用于私有仓库的Pages）
- 每次推送到main分支都会自动触发重新部署
