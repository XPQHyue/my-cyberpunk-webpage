# 我的赛博朋克网页

一个使用 GitHub Pages 托管的现代化静态网页，采用赛博朋克风格设计。

## ✨ 特性

- 🎨 现代赛博朋克风格设计
- 🚀 渐变色彩和玻璃态效果
- 💫 流畅的CSS动画
- 📱 完全响应式设计
- ⚡ 高性能静态页面

## 🚀 快速开始

### 方法一：通过GitHub网页界面部署

1. **创建GitHub仓库**
   - 访问 [GitHub](https://github.com) 并登录
   - 点击右上角 "+" → "New repository"
   - 仓库名称：`my-cyberpunk-webpage`（或你喜欢的名称）
   - 选择 "Public" 或 "Private"
   - 勾选 "Initialize this repository with a README"
   - 点击 "Create repository"

2. **上传文件**
   - 在仓库页面，点击 "Add file" → "Upload files"
   - 拖拽或选择 `index.html` 文件
   - 在 "Commit changes" 中填写："添加初始网页"
   - 点击 "Commit changes"

3. **启用GitHub Pages**
   - 进入仓库页面
   - 点击 "Settings" 标签
   - 在左侧菜单中找到 "Pages"
   - 在 "Build and deployment" 部分：
     - Source: 选择 "Deploy from a branch"
     - Branch: 选择 `main` 分支，文件夹选择 `/ (root)`
   - 点击 "Save"

4. **等待部署完成**
   - 等待约1-3分钟
   - 刷新Pages页面，会显示你的网站地址
   - 格式通常是：`https://你的用户名.github.io/仓库名/`

### 方法二：通过Git命令行部署

```bash
# 1. 初始化本地仓库
git init

# 2. 添加所有文件
git add .

# 3. 提交更改
git commit -m "添加初始网页"

# 4. 添加远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/你的用户名/你的仓库名.git

# 5. 推送到GitHub
git push -u origin main

# 6. 然后按照方法一的步骤3-4启用GitHub Pages
```

## 📝 本地开发流程

```bash
# 克隆仓库到本地
git clone https://github.com/你的用户名/你的仓库名.git
cd 你的仓库名

# 修改文件后，查看更改
git status

# 添加修改的文件
git add .

# 提交更改
git commit -m "更新网页内容"

# 推送到GitHub
git push

# GitHub Pages会自动重新部署你的网站
```

## 🎨 自定义你的网页

编辑 `index.html` 文件，你可以：

1. **修改标题和内容**
   - 找到 `<h1>` 标签修改主标题
   - 找到 `<p>` 标签修改文本内容

2. **更改颜色主题**
   - 在 `<style>` 标签中修改渐变颜色
   - 搜索 `linear-gradient` 可以找到所有渐变设置

3. **添加新内容**
   - 在 `.features` 部分添加新的卡片
   - 在 `.section` 部分添加新的内容区块

## 🌐 访问你的网站

部署成功后，你的网站地址格式为：
```
https://你的用户名.github.io/仓库名/
```

## 📚 常用Git命令

```bash
# 查看当前状态
git status

# 查看提交历史
git log

# 拉取最新代码
git pull

# 创建新分支
git branch 分支名

# 切换分支
git checkout 分支名

# 合并分支
git merge 分支名
```

## 🛠️ 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 现代样式和动画
- **JavaScript** - 粒子效果
- **GitHub Pages** - 免费静态网站托管
- **Git** - 版本控制系统

## 📖 学习资源

- [GitHub Pages 官方文档](https://docs.github.com/en/pages)
- [Git 官方文档](https://git-scm.com/doc)
- [MDN Web 文档](https://developer.mozilla.org/zh-CN/)

## 📝 许可证

MIT License

## 💡 提示

- 每次修改文件后，记得提交并推送到GitHub
- GitHub Pages会自动检测到更改并重新部署
- 首次部署可能需要几分钟时间
- 如果遇到问题，检查仓库的 "Actions" 标签查看部署日志

---

**享受你的赛博朋克网页之旅！** 🚀✨