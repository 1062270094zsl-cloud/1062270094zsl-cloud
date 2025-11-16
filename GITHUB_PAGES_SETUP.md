# GitHub Pages 设置指南

## 🚀 将网页设置为 GitHub 个人主页

### 步骤 1: 启用 GitHub Pages

1. 访问您的 GitHub 个人主页仓库：`https://github.com/1062270094zsl-cloud/1062270094zsl-cloud`
2. 点击 **Settings** (设置)
3. 在左侧菜单中找到 **Pages**
4. 在 **Source** 下选择 **Deploy from a branch**
5. 选择分支：`main` (或 `master`)
6. 选择文件夹：`/ (root)` 或 `/github-profile` (如果文件在子目录)
7. 点击 **Save** (保存)

### 步骤 2: 访问您的网页

设置完成后，您的网页将在以下地址可用：
- `https://1062270094zsl-cloud.github.io/1062270094zsl-cloud/`

### 步骤 3: 更新 README.md

README.md 已经更新，包含指向网页的链接。

### 文件结构

```
1062270094zsl-cloud/
├── README.md          # 个人主页 README（包含网页链接）
├── index.html         # 网页主页
├── assets/            # 资源文件
│   ├── profile.jpg
│   └── resume/
│       └── resume_zh.pdf
└── .nojekyll          # 禁用 Jekyll（已创建）
```

### 注意事项

- `.nojekyll` 文件已创建，用于禁用 Jekyll 处理
- 确保所有资源文件路径正确
- GitHub Pages 可能需要几分钟才能生效

### 自定义域名（可选）

如果您有自定义域名，可以在 Pages 设置中添加。

