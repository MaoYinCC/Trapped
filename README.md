# 憋死牛 (Don't Get Trapped)

一个基于 HTML5、CSS3 和 JavaScript 开发的经典民间棋类游戏——“憋死牛”（也称“闯井”），支持人机对战、本地双人对战，以及通过 PeerJS 实现的零成本 P2P 联网对战。

## 即开即玩：
https://maoyincc.github.io/Trapped/

## 🎮 游戏规则

* **棋盘与初始布局**：棋盘由外围正方形对角线、底边及中心点组成（共 5 个节点）。红方（P1）与蓝方（P2）各拥有 2 枚棋子，初始时正方形上方和下方各有一枚空位或特定布局。
* **移动规则**：棋子每次只能沿棋盘上的线条移动一步，走到相邻的空节点上。
* **胜负判定**：如果一方的所有棋子均被堵住，无法移动（即被“憋死”），则另一方获胜。

## ✨ 主要功能

* **多种对战模式**：
  * **人机对战 (PvE)**：单人游玩，与电脑 AI 进行对决。
  * **双人对战 (PvP)**：本地双人同屏对抗。
  * **联机对战 (Online)**：基于 PeerJS 的 P2P 联网功能，通过输入 4 位数房间号即可与远端好友实时联机。
* **灵活的先手选择**：联机或单人模式下，支持随时在控制面板中切换**红方先手**或**蓝方先手**，修改后自动实时同步并重置棋局。
* **多语言支持**：内置中英文一键切换（`🌐 EN` / `🌐 中`）。
* **沉浸式音效**：使用 Web Audio API 内置纯前端合成音效（落子声、选中声、胜利提示音），支持音效一键静音。
* **优雅的视觉设计**：木纹质感棋盘、细腻的棋子光影及动态提示动画。

## 🚀 快速开始

本项目为纯前端单文件应用（Single-File Component），无需配置复杂的构建环境。

1. 克隆或下载本仓库的 `index.html` 文件。
2. 双击该文件，或在任意现代浏览器（Chrome, Firefox, Safari, Edge）中直接打开即可开始游戏。
3. 若需体验**联机对战**功能，请确保设备已连接互联网（项目通过公共 CDN 引入了 PeerJS 库）。

## 📂 项目结构

* 单文件架构，所有 HTML、CSS 样式及 JavaScript 游戏逻辑均包含在 `index.html` 中：
  * **UI 布局与样式**：基于原生 CSS 变量及 Flexbox 布局，适配多终端。
  * **联机模块**：基于 `PeerJS` 实现点对点（P2P）信令与数据同步。
  * **音效模块**：原生 `AudioContext` 合成音效，无需加载外部音频文件。

## 📜 许可证

本项目采用 MIT 许可证开源，欢迎自由分发与修改。

## 即开即玩：
https://maoyincc.github.io/Trapped/


# Don't Get Trapped (憋死牛)

A classic folk board game developed using HTML5, CSS3, and JavaScript—known as "Don't Get Trapped" (also called "Chuangjing"). It supports Player vs. Environment (PvE), local two-player battles, and zero-cost P2P online multiplayer powered by PeerJS.

## Play Instantly:

[https://maoyincc.github.io/Trapped/](https://maoyincc.github.io/Trapped/)

## 🎮 Game Rules

* **Board & Initial Layout**: The board consists of an outer square with diagonals, a bottom line, and a center point (total of 5 nodes). Red (P1) and Blue (P2) each own 2 pieces, starting at designated positions on the upper and lower sections of the square.
* **Movement Rules**: Pieces can only move one step along the lines on the board to an adjacent empty node.
* **Victory Condition**: If all of a player's pieces are blocked and unable to move (i.e., "trapped"), the opponent wins.

## ✨ Key Features

* **Multiple Game Modes**:
* **PvE (Player vs. AI)**: Play solo against a computer opponent.
* **PvP (Local Two-Player)**: Face off locally on the same screen.
* **Online Multiplayer**: Real-time peer-to-peer online matching via PeerJS using a simple 4-digit room code.


* **Flexible Turn Selection**: Easily switch whether Red or Blue goes first in single-player or online modes using the control panel, with real-time sync and automatic board reset upon change.
* **Multi-Language Support**: Built-in one-click toggle between English and Chinese (`🌐 EN` / `🌐 中`).
* **Immersive Sound Effects**: Pure front-end synthetic sound effects powered by the Web Audio API (placement sounds, selection cues, victory alerts) with a one-click mute option.
* **Elegant Visual Design**: Wood-textured board, delicate piece shadows, and dynamic prompt animations.

## 🚀 Quick Start

This project is a pure front-end single-file application requiring no complex build environments.

1. Clone or download the `index.html` file from this repository.
2. Double-click the file or open it directly in any modern browser (Chrome, Firefox, Safari, Edge) to start playing.
3. To experience the online multiplayer feature, ensure your device is connected to the internet (the project loads the PeerJS library via a public CDN).

## 📂 Project Structure

* **Single-File Architecture**: All HTML, CSS styles, and JavaScript game logic are encapsulated within a single `index.html` file:
* **UI Layout & Styles**: Built with native CSS variables and Flexbox layout, fully responsive across multiple devices.
* **Networking Module**: Implements peer-to-peer (P2P) signaling and data synchronization via `PeerJS`.
* **Sound Module**: Native `AudioContext` synthesized sound effects, requiring no external audio asset files.



## 📜 License

This project is open-sourced under the MIT License, welcoming free distribution and modification.

## Play Instantly:

[https://maoyincc.github.io/Trapped/](https://maoyincc.github.io/Trapped/)
