# Pygame Tetris (Enhanced Version)
*A customized Tetris implementation with extended features and optimized logic.*

## 📌 Introduction | 项目介绍
This is a desktop mini-game built with **Python** and the **Pygame** library. It features a complete game loop, UI systems, and customized game logic.

---

## ✨ New Features | 新增特性
Derived from the core logic of [this tutorial](https://www.bilibili.com/video/BV19u4y1B7br/), I have implemented the following enhancements:
* **Advanced Collision Detection:** Refined movement and rotation constraints. (优化了移动与旋转判定)
* **Game Mechanics:** Multi-row elimination and boundary constraints. (实现多行消除与边界限制)
* **UI/UX:** Added Start/Game Over screens, pausing, and navigation menus. (增加开始/结束界面、暂停及菜单功能)
* **Audio:** Integrated background music for different game states. (为不同场景添加背景音乐)
* **Code Refactoring:** Fixed multiple bugs and optimized state management. (修复 Bug 并优化状态管理)

---

## 📂 Project Structure | 文件结构
* `main.py`: Entry point; manages window lifecycle. (程序入口，管理窗口生命周期)
* `game.py`: Core game loop and logic. (核心游戏逻辑)
* `block.py` & `blockGroup.py`: OOP implementation for tetrominoes and their behaviors. (利用面向对象实现方块及其组合)
* `menu.py`: UI menu system. (菜单系统)
* `const.py` & `utils.py`: Constants and helper functions. (常量与工具函数)

---

## 🛠️ How to Run | 如何运行
Ensure you have Python and Pygame installed:
```bash
pip install pygame
python main.py

 

