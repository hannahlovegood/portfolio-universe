# 作品小宇宙 · Portfolio Universe

一个可以**走进去**的 3D 作品集 —— 站在房间正中，用 `WASD` / 方向键走动、拖拽环顾，点击任意物件打开对应项目卡。

🔗 **Live:** https://hannahlovegood.github.io/portfolio-universe/

## 操作

- **移动**：`W` `A` `S` `D` / 方向键
- **环顾**：按住鼠标拖拽
- **查看**：点击物件（或点物件上方的浮动标签）打开项目卡 → 跳转真实项目

## 技术

- 纯单文件 `index.html`，零构建、可离线打开
- [Three.js](https://threejs.org/)（WebGL，经 CDN 引入）手写场景 / 第一人称控制 / 射线点击
- 6 个物件用基础几何体搭成，可在文件顶部 `PROJECTS` 数组里替换成你自己的项目

## 自定义

打开 `index.html`，改顶部：

- `OWNER`：你的名字（显示在标题）
- `PROJECTS`：每个项目的 `name / en / desc / tags / link / color / shape`

## 致谢

形式受 [Bruno Simon — My Room in 3D](https://my-room-in-3d.vercel.app/) 启发，从零用 Three.js 重写，未使用其代码或资源。
