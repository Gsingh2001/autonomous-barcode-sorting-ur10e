# 📦 Autonomous Barcode-Based Object Sorting Using UR10e

## 🚀 Project Overview
This project demonstrates an **AI-powered robotic arm system** using the **UR10e manipulator** and **Robotiq 3F Gripper** for **automated object sorting** based on **barcode detection**. The system utilizes **Webots simulation**, **OpenCV**, and **Pyzbar** to detect barcodes, grasp objects, and place them in predefined locations.

## 🔧 Features
✅ **Real-time Barcode Detection** using OpenCV & Pyzbar  
✅ **Autonomous Object Sorting** based on barcode data  
✅ **UR10e Robotic Arm Control** with precise joint movements  
✅ **State-Based Task Execution** (Grasping, Rotating, Releasing)  
✅ **Sensor Integration** for accurate object detection and positioning  

## 🛠 Technologies Used
- **Webots** – Robotics simulation environment  
- **Python** – Core scripting language  
- **OpenCV & Pyzbar** – Computer vision & barcode detection  
- **UR10e API** – Robotic arm control  
- **Robotiq 3F Gripper API** – Object grasping & manipulation  

## 📂 Project Structure
```
📦 autonomous-barcode-sorting-ur10e
├── 📂 webots
│   ├── 📂 worlds
│   │   ├── sorting_simulation.wbt
│   ├── 📂 controllers
│   │   ├── sorting_controller.py
├── 📂 assets
│   ├── final.png
```

## 🏗 Setup & Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/autonomous-barcode-sorting-ur10e.git
cd autonomous-barcode-sorting-ur10e
```

### 2️⃣ Install Dependencies
```bash
pip install opencv-python pyzbar numpy
```

### 3️⃣ Run the Webots Simulation
#### ➤ Open Webots and load the world file
- Navigate to `webots/worlds/` and open **`sorting_simulation.wbt`** in Webots.

#### ➤ Run the Webots Simulation
```bash
webots ./webots/worlds/sorting_simulation.wbt
```

## 📸 Demo
![Robotic Sorting Process](assets/final.png)

## 🤖 Future Improvements
- Enhance **path planning & inverse kinematics** for smoother motion  
- Implement **deep learning-based barcode recognition** for better accuracy  
- Extend to **physical robotic arm deployment**  

## 📜 License
This project is **open-source** under the **MIT License**.

🔗 **Check the Full Code Here:** [GitHub Repository](https://github.com/Gsingh2001/autonomous-barcode-sorting-ur10e)  

---
