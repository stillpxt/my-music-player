# 8歌歌歌 (8 Gegege)

一个个人音乐作品展示与交互式网页项目。本项目为“粤语唱见”打造，提供独特的视觉交互和音频播放体验。

## 项目特点

- **沉浸式视觉体验**：支持背景图像切换与全屏预览，具备流畅的过渡动画与 3D 悬浮视差效果。
- **互动语音播放**：集成个人简介相关的语音互动（如年龄、擅长乐器、业余爱好等），支持点击动态声波效果。
- **全局悬浮播放器 (Dock Player)**：页面底部提供悬浮音乐播放器，支持切歌、播放/暂停、收藏等功能。
- **多页面导航**：支持侧边栏快捷导航，实现页面间的快速跳转及平滑滚动。
- **响应式设计**：完美适配不同屏幕尺寸，在桌面端和移动端均能提供优秀的交互体验。

## 目录结构

```text
├── .vscode/          # VSCode 配置文件
├── assets/
│   └── media/        # 静态资源目录
│       ├── audio/    # 音频文件
│       ├── background/ # 背景图片
│       └── cover/    # 封面图片
├── index.html        # 首页
├── page2.html        # 其他展示页面
├── page3.html
├── page4.html
├── page5.html
├── page6.html
└── song-detail.html  # 歌曲详情页
```

## 技术栈

- HTML5
- CSS3 (原生 CSS 变量, Grid/Flexbox 布局, 动画与滤镜)
- 原生 JavaScript (ES6+, DOM 操作, Audio API)

## 运行方式

由于项目包含本地音频和模块等资源，建议通过本地服务器运行以获得最佳体验（直接双击打开 HTML 可能因为跨域策略导致部分资源加载异常）。

你可以使用以下任意一种方式启动本地服务：

- **VS Code Live Server 插件**：在 VS Code 中右键点击 `index.html`，选择 "Open with Live Server"。
- **Python HTTP Server**：在项目根目录下运行 `python -m http.server 8000`，然后在浏览器访问 `http://localhost:8000`。
- **Node.js http-server**：运行 `npx http-server`。

## 浏览器兼容性

推荐使用现代浏览器（如 Chrome, Edge, Firefox, Safari 等）以获得最佳视听体验。
