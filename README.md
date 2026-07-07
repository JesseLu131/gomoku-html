# ✨ 流光五子棋 (Gomoku Master)

一个精美的单文件 HTML 五子棋游戏，支持双人对战和人机对战，带有粒子动画背景、毛玻璃 UI 和 Web Audio 音效。

## 🎮 在线试玩

**部署中...** 需要先启用 GitHub Pages：

1. 打开 [Settings → Pages](https://github.com/JesseLu131/gomoku-html/settings/pages)
2. 在 **Source** 下拉框选择 **Deploy from a branch**
3. 在 **Branch** 下拉框选择 **main** / **(root)**
4. 点击 **Save**

等待约 1-2 分钟后即可访问：
```
https://jessele131.github.io/gomoku-html/
```

## 🎯 功能特性

- **双人对战** — 两位玩家本地对战
- **人机对战** — 4 档 AI 难度（简单/中等/困难/大师）
- **Canvas 渲染** — 精美棋盘、粒子背景、落子动画
- **音效系统** — Web Audio API 落子和胜利音效
- **走棋记录** — 完整棋谱记录，支持悔棋
- **计时系统** — 黑白双方独立计时
- **响应式布局** — 适配桌面和移动端

## 🛠️ 技术栈

纯前端单文件，无需任何依赖：
- HTML5 Canvas 2D
- Web Audio API
- requestAnimationFrame
- CSS3 动画与毛玻璃效果

## 🖥️ 本地运行

直接双击 `index.html` 在浏览器中打开即可，无需服务器。

## 📁 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 完整游戏（单文件，约 35KB） |
| `gomoku.html` | 同内容备用文件 |

## ⚡ Electron 桌面版

项目同时提供 Electron 打包版本，可生成 Windows `.exe` 独立运行程序。

---

Made with ❤️ by JesseLu131
