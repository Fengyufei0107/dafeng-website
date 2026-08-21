# 大冯的网站学习手册

这是大冯从零开始学习制作网站的长期笔记。

学习目标：慢慢理解网站是怎样制作、保存、上传和发布的，并亲手维护自己的第一个网站。

## 我的网站

- 网站名称：大冯的网页
- 在线地址：<https://fengyufei0107.github.io/dafeng-website/>
- GitHub 仓库：<https://github.com/Fengyufei0107/dafeng-website>

## 2026-08-20：完成第一个网站

### 1. 什么是 GitHub 仓库

GitHub 仓库可以理解为一个放在网上的“项目文件夹”。

它可以：

- 保存网站文件；
- 记录每次修改；
- 找回以前的版本；
- 与别人分享或合作。

### 2. 网站的三个基础部分

#### HTML：网页的内容

HTML 决定网页里有什么，例如标题、文字、图片和按钮。

```html
<h1>欢迎来到大冯的网页</h1>
```

`h1` 表示网页中最重要的大标题。

#### CSS：网页的外观

CSS 决定网页的颜色、大小、位置和布局。

```css
h1 {
  color: purple;
}
```

这段代码会把大标题变成紫色。

#### JavaScript：网页的互动

JavaScript 让网页能够对操作作出反应。

```javascript
function showMessage() {
  alert("你好，欢迎来做客！");
}
```

这段代码会在点击按钮后弹出一条消息。

可以简单记成：

> HTML 管内容，CSS 管外观，JavaScript 管互动。

### 3. 我认识的网站文件

```text
dafeng-website
├── index.html
├── about.html
├── style.css
├── script.js
└── images
    └── sailboat.jpg
```

- `index.html`：网站首页；
- `about.html`：“关于大冯”页面；
- `style.css`：两个页面共用的外观；
- `script.js`：按钮的互动功能；
- `images`：专门存放图片的文件夹。

### 4. 文件地址

网页通过文件地址找到其他页面和图片。

```html
<a href="about.html">了解大冯</a>
<img src="images/sailboat.jpg" alt="月光下海面上的帆船">
```

- `about.html` 和首页在同一个文件夹中，可以直接写文件名；
- `sailboat.jpg` 在 `images` 文件夹中，所以要写 `images/sailboat.jpg`；
- 文件名或位置改变后，代码里的地址也要跟着改变。

### 5. GitHub 中遇到的英文

- `Repository`：仓库；
- `Public`：公开；
- `Upload files`：上传文件；
- `Commit changes`：提交更改，保存一次修改记录；
- `Settings`：设置；
- `Pages`：把仓库里的静态网页发布到互联网；
- `main`：项目的主要分支；
- `/(root)`：仓库最外层。

### 6. 我完成的发布流程

```text
在电脑上制作网页
→ 创建 GitHub 仓库
→ 上传网站文件
→ 开启 GitHub Pages
→ 获得公开网址
```

## 当前进度

- [x] 创建第一个 HTML 页面
- [x] 使用 CSS 美化页面
- [x] 使用 JavaScript 添加按钮互动
- [x] 创建“关于大冯”页面
- [x] 添加图片
- [x] 创建 GitHub 仓库
- [x] 使用 GitHub Pages 发布网站
- [ ] 学习怎样修改并更新已发布的网站
- [ ] 学习 Git 和版本记录
- [ ] 继续完善网站内容与样式

## 一句话复习

> 网站文件保存在 GitHub 仓库中，GitHub Pages 把这些文件发布成别人可以访问的网站。

## 后续学习记录

以后每次学习后，在这里继续增加新的日期和内容。

