# 🧭 Maze Path Finder (BFS + Curses)

A terminal-based Maze Path Finder built using Python and the `curses` module.  
The algorithm uses **Breadth-First Search (BFS)** to find the shortest path from the start (`O`) to the goal (`X`) in a grid maze.

The maze-solving process is visually animated in the terminal, showing how the BFS explores the maze step-by-step.

---

## 🚀 Features

- 🔍 **Breadth-First Search (BFS)** shortest-path algorithm  
- 🎨 **Colorized terminal visualization** using curses  
- 🧱 **Walls**, **empty spaces**, **start**, and **end** clearly displayed  
- 🛣 **Real-time animation** of BFS exploring nodes  
- ✔ **Shortest path is highlighted** in red  
- 🗺 Fully editable maze matrix  

---

## 📊 How It Works

1. Maze is represented as a 2D grid:
   - `#` = wall  
   - `O` = start  
   - `X` = end  
   - `" "` = walkable path  

2. BFS is run from the start node, storing paths in a queue.

3. At each step:
   - The screen refreshes  
   - Current explored path is shown  
   - Neighboring cells are added to the queue  

4. Once `X` is reached, the final path is drawn.

---

## 🧠 Concepts Demonstrated
- Breadth-First Search (shortest path in unweighted graphs)  
- Terminal UI programming with `curses`  
- Path reconstruction using parent tracking  
- Queue-based graph traversal  
- Real-time visualization  
- Matrix-based maze navigation  

---

## ▶️ Run the Project

### **1. Install curses (Linux/macOS only)**
Curses works natively on macOS and Linux.  
On Windows, install:

```bash
pip install windows-curses
```
### **2.Run the script**

```
python3 path_finder.py
```
