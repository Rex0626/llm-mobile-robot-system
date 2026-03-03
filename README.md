# 🤖 LLM Mobile Robot System  
大型語言模型與行動機器人整合系統  
LLM-Integrated ROS2 Mobile Robot Framework  

---

## 📖 專案介紹 | Project Overview

本專案旨在結合 **ROS2 行動機器人系統** 與 **大型語言模型（LLM）**，  
打造具備自然語言理解能力的智慧型行動機器人。

This project aims to integrate **ROS2-based mobile robots** with  
**Large Language Models (LLM)** to build an intelligent robotic interaction system.

長期目標是讓機器人能夠：
- 理解人類自然語言指令  
- 自主規劃移動路徑  
- 執行任務與環境互動  

The long-term goal is to enable robots to:
- Understand natural language commands  
- Plan navigation autonomously  
- Execute tasks intelligently  

---

## 🎯 開發階段 | Development Roadmap

### ✅ Phase 1 – 環境建置 Environment Setup (Completed)
- ROS2 安裝與設定完成  
- TurtleBot3 模擬成功  
- Gazebo 環境測試完成  
- Teleop 鍵盤控制驗證  

---

### 🔄 Phase 2 – 系統架構設計 System Architecture (In Progress)
- ROS2 套件架構規劃  
- Node 通訊流程設計  
- LLM 整合架構設計  

---

### ⏳ Phase 3 – 智慧語言互動 Intelligent Interaction
- 自然語言指令解析  
- LLM 與 ROS2 橋接節點  
- 任務規劃與動作執行  

---

## 🛠️ 技術架構 | Tech Stack

- ROS2 Humble  
- TurtleBot3  
- Gazebo  
- Python (ament_python)  
- Ubuntu / WSL  

---

## 🚀 執行方式 | How to Run

```bash
# 建置工作空間 Build workspace
colcon build

# 載入環境變數 Source environment
source install/setup.bash

# 啟動模擬 Launch simulation
ros2 launch turtlebot3_gazebo empty_world.launch.py
```

# 📁 專案結構 | Project Structure
## llm-mobile-robot-system/
  │
  ├── src/                  # ROS2 套件 Packages
  ├── build/                # 建置輸出 Build artifacts
  ├── install/              # 安裝檔 Installation
  ├── log/                  # 系統紀錄 Logs
  ├── README.md
  └── .gitignore

# 🧠 系統願景 | System Vision
## 未來使用者可以輸入：
### Future users may say:
- 「前往廚房」 / "Go to the kitchen"
- 「巡邏整個房間」 / "Patrol the room"
- 「尋找障礙物」 / "Find obstacles"

## 系統流程將為：
### System pipeline:
1. 使用 LLM 解析語意
2. 轉換為結構化機器人指令
3. 透過 ROS2 節點執行

# 👤 作者 | Author
- Rex Tham
- Computer Science Student
- Robotics & AI System Development

# 📜 授權 | License
- 本專案僅供研究與學術用途。
- This project is for research and educational purposes only.