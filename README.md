# 作品小宇宙 · Portfolio Universe

一个可以**走进去**的 3D 作品集 —— 星空下的环形广场，四个主题星区环绕中央纪念碑，收录 **27 件已上线的真实作品**。用 `WASD` / 方向键（手机为虚拟摇杆）走动、拖拽环顾，点击任意物件打开对应项目卡。

🔗 **Live:** https://hannahlovegood.github.io/portfolio-universe/

## 四个星区

- **游戏与叙事**：命定回响 / 重启人生·2008 / 换乘 / COIN RUSH / Phaser 平台闯关 / 躲避小怪
- **AI 与工程**：Hermes / TraceRAG / 信息雷达 / Flowise RAG / RAGFlow / Firecrawl / Karakeep / SearXNG / AFFiNE
- **工具与效率**：读墨 / 24小时人生拨盘 / 墨链 / 墨水屏日历牌 / 手绘风 UI 组件 / 爆款视频工坊
- **创意与表达**：B-Side 鲸落 / 算法节奏乐队 / 粒子实验室 / Synora / 看见少数人

中央纪念碑链接到策展版 [Portfolio 主页](https://hannahlovegood.github.io/portfolio/)。

## 操作

- **移动**：`W` `A` `S` `D` / 方向键；触屏设备左下角虚拟摇杆
- **环顾**：按住拖拽
- **查看**：点击物件（或物件上方的浮动标签）打开项目卡 → 跳转真实项目

## 技术

- 纯单文件 `index.html`，零构建、无依赖打包（Three.js 经 CDN 引入）
- 手写第一人称控制 / 射线点击 / 圆形边界与基座碰撞
- 27 件展品各有一个用基础几何体搭成的**专属造型**（雷达、节点图、双星、唱机、打字台……）
- 星区铭牌为 Canvas 贴图 Sprite；地面星区色带 + 星空粒子；ACES 色调映射

## 自定义

打开 `index.html`，改顶部数据区：

- `OWNER`：你的名字（显示在标题）
- `ZONES`：四个星区及各自的项目（`name / en / desc / tags / link / color / shape`）
- `CENTER`：中央纪念碑指向的链接

## 致谢

形式受 [Bruno Simon — My Room in 3D](https://my-room-in-3d.vercel.app/) 启发，从零用 Three.js 重写，未使用其代码或资源。
