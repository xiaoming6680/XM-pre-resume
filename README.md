# AI Resume Portfolio

推荐仓库名：`ai-resume-portfolio`

这是一个单文件静态个人主页型网页简历，用来展示我的学习路径、课程项目、技能工具、内容平台入口和个人联系方式。页面整体采用黑白高对比、暗色玻璃导航、卡片式项目展示、图片渐变过渡和底部动态光晕效果。

## 项目亮点

- 单文件运行：核心页面为 `index.html`，CSS 和 JavaScript 都写在文件内。
- 响应式适配：桌面端和移动端都可以浏览。
- 锚点导航：顶部导航可以快速跳转到项目、关于我、学习路径、技能工具、生活平台和联系方式。
- 项目网格：作品和经历信息使用卡片展示，避免长段落堆砌。
- 技能展示：技能和背书区域使用图表、标签和卡片组织信息。
- 视觉过渡：使用 `W to B.png` 和 `B to W.png` 作为黑白页面之间的渐变衔接。
- 动态效果：页面加载、卡片出现、指南针滚动和底部光晕都有轻量交互效果。
- 平台入口：生活平台卡片使用 Simple Icons CDN 加载 GitHub、Bilibili、小红书和微信 Logo。

## 技术栈

- HTML5
- CSS3
- Vanilla JavaScript
- Simple Icons CDN
- GitHub Pages

## 文件结构

```text
.
├── index.html        # 网站入口文件
├── W to B.png        # 白色到黑色过渡素材
├── B to W.png        # 黑色到白色过渡素材
├── PRDs/             # 产品需求文档
├── design/           # UI 设计文档
└── README.md
```

## 本地预览

直接在浏览器中打开 `index.html` 即可。

也可以在 PowerShell 中运行：

```powershell
Start-Process .\index.html
```

## 发布到 GitHub Pages

1. 在 GitHub 新建仓库，推荐名称：`ai-resume-portfolio`。
2. 将本项目文件提交到仓库。
3. 在仓库页面进入 `Settings` -> `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub Pages 构建完成。

常用提交命令：

```powershell
git add index.html README.md "W to B.png" "B to W.png" PRDs design
git commit -m "Add static resume website"
git branch -M main
git remote add origin https://github.com/<your-username>/ai-resume-portfolio.git
git push -u origin main
```

如果已经添加过远程仓库，可以改用：

```powershell
git remote set-url origin https://github.com/<your-username>/ai-resume-portfolio.git
git push -u origin main
```

## 素材和说明

- 页面渐变素材来自本项目目录中的 `W to B.png` 和 `B to W.png`。
- 平台 Logo 通过 Simple Icons CDN 加载，相关品牌归各自所有者所有。
- 当前内容以个人学习、课程项目和作品展示为主，后续可以继续补充真实项目链接、演示视频、截图和正式经历。

## 后续计划

- 补充项目仓库链接和在线演示地址。
- 增加真实项目截图或录屏。
- 完善英文版内容。
- 根据后续实习、社团或项目经历更新简历内容。

## License

未指定开源协议前，保留所有权利。
