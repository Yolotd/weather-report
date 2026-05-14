# GitHub Pages 部署指南

## 第一步：准备HTML文件

已为您准备好在线天气报告HTML文件：`天气报告_在线版.html`

## 第二步：登录GitHub

1. 打开浏览器，访问：https://github.com
2. 登录您的GitHub账号

## 第三步：创建新仓库

1. 点击右上角的 "+" 号，选择 "New repository"
2. 填写仓库信息：
   - Repository name: `weather-report` （或任意名称）
   - Description: `广州天河区珠村文华大街天气报告`
   - 选择 "Public"（公开）
   - ✅ 勾选 "Add a README file"
3. 点击 "Create repository"

## 第四步：上传HTML文件

1. 在仓库页面，点击 "Add file" → "Upload files"
2. 将 `天气报告_在线版.html` 文件拖拽到上传区域
3. 在文件名输入框中，将文件重命名为 `index.html`
4. 在 "Commit changes" 区域填写提交信息，如："添加天气报告"
5. 点击 "Commit changes"

## 第五步：启用GitHub Pages

1. 在仓库页面，点击 "Settings"（设置）
2. 在左侧菜单找到 "Pages"
3. 在 "Source" 部分：
   - Branch: 选择 "main"
   - Folder: 选择 "/ (root)"
4. 点击 "Save"
5. 等待1-2分钟，页面会刷新并显示：
   ```
   Your site is live at https://[您的用户名].github.io/weather-report/
   ```

## 第六步：访问您的天气报告

访问链接：`https://[您的用户名].github.io/weather-report/`

## 特点

- ✅ 永久免费
- ✅ 全球访问
- ✅ 自动获取实时天气（使用wttr.in免费API）
- ✅ 手机、电脑都能访问
- ✅ 支持HTTPS安全访问
- ✅ 每10分钟自动刷新

## 常见问题

**Q: 为什么显示"Page not found"？**
A: 请等待1-2分钟，GitHub Pages需要时间部署

**Q: 如何更新天气报告？**
A: 点击页面上的"刷新页面"按钮，或直接刷新浏览器

**Q: 可以自定义域名吗？**
A: 可以！在Settings → Pages → Custom domain中设置

**Q: 如何修改天气报告内容？**
A: 在GitHub仓库中找到index.html文件，点击编辑，修改后提交即可

## 备用方案：使用Gitee Pages

如果GitHub访问较慢，可以使用Gitee（码云）：

1. 访问：https://gitee.com
2. 注册/登录账号
3. 创建新仓库，上传HTML文件
4. 在"服务" → "Gitee Pages"中启用
5. 获得访问链接：`https://[用户名].gitee.io/[仓库名]/`

---

**需要帮助？**
如果在部署过程中遇到任何问题，请告诉我！
