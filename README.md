# Pygame Tetris (Enhanced Version)
*A customized Tetris implementation with extended features and optimized logic.*


## 🌱 My Programming Enlightenment | 编程启蒙

This project marks the very beginning of my coding journey and my passion for software development. 
**In fact, I have dreamed of becoming a game developer since high school.** Now, as a **Chemistry major**, I am channeling that same creative spark into **AI for Science (AI4S)** to explore the intersection of code and molecules.(I am proud to share that this project earned a perfect score of **100/100** in my Python programming course.)

这个项目标志着我编程之路的开端，也是我开发热情的起点。
事实上，我从高中开始就想成为一名游戏开发者。如今作为一名**化学专业**的学生，我正将这份热情投入到 AI for Science，探索代码与分子世界的交汇点。（很高兴凭借这个课程设计，我在大一的 Python 课程获得了 **100分** 。）

---

## 📌 Introduction | 项目介绍
This is a desktop mini-game built with **Python** and the **Pygame** library. It features a complete game loop, UI systems, and customized game logic.

本项目是基于 Pygame 开发的俄罗斯方块增强版，实现了完整的游戏循环、UI 系统及优化的逻辑判定。

## ✨ New Features | 新增特性
Derived from the core logic of [this tutorial](https://www.bilibili.com/video/BV19u4y1B7br/), I have implemented the following enhancements:
在原版逻辑基础上，本项目增加了以下特性：
* **Advanced Collision Detection:** Refined movement and rotation constraints. (优化了移动与旋转判定)
* **Game Mechanics:** Multi-row elimination and boundary constraints. (实现多行消除与边界限制)
* **UI/UX:** Added Start/Game Over screens, pausing, and navigation menus. (增加开始/结束界面、暂停及菜单功能)
* **Audio:** Integrated background music for different game states. (为不同场景添加背景音乐)
* **Code Refactoring:** Fixed multiple bugs and optimized state management. (修复 Bug 并优化状态管理)


## 📂 Project Structure | 文件结构
* `main.py`: Entry point; manages window lifecycle. (程序入口，管理窗口生命周期)
* `game.py`: Core game loop and logic. (核心游戏逻辑)
* `block.py` & `blockGroup.py`: OOP implementation for tetrominoes and their behaviors. (利用面向对象实现方块及其组合)
* `menu.py`: UI menu system. (菜单系统)
* `const.py` & `utils.py`: Constants and helper functions. (常量与工具函数)

---

## 🛠️ How to Run | 如何运行
### 1. Pre-built Executable (Windows)
Double-click the `.exe` file in the folder (packaged via Pyinstaller). 
**Note:** Do not move the executable out of the folder, as it relies on local `assets/` (images/music).

### 2. Run from Source
Ensure you have Python and Pygame installed:
```bash
pip install pygame
python main.py
