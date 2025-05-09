# Autonomous Driving Without Lane Marks

## 📌 Jira Link  
[Click here to view our project board](https://yourteam.atlassian.net/jira/software/projects/ADWL/boards/1)

## 🚗 Project Overview  
This project focuses on developing a software system that enables autonomous vehicles to drive safely on roads where lane markings are unclear, damaged, or completely absent. The algorithm is tested in both a simulator and a prototype car.

## 🎯 Objectives  
- Build an autonomous driving algorithm that does not rely on visible lane markings.
- Process real-time sensor input to navigate safely and effectively.
- Support testing in both simulated and physical environments.

## 🎯 Goals and Motivation  
Traditional self-driving systems rely heavily on lane detection, making them less effective in real-world conditions like poor weather or road work. This project aims to fill that gap by developing a more flexible driving strategy that can adapt in those environments.

## 📁 Project Structure  
/algorithm - Core C++ processing and response modules
/simulator - Scripts and config files for simulation testing
/prototype - Raspberry Pi hardware setup and test instructions
/docs - Software design documents, SRS, and development snapshots
/tests - Unit and integration test cases


## ⚙️ How to Use

### 1. Clone the Repository
```bash
git clone (https://github.com/TeamCoolKats/Autonomous-Driving-Car)
cd Autonomous-Driving-Car

For Simulation (Python-based):
Python 3.9 or later

OpenCV (pip install opencv-python)

NumPy (pip install numpy)

For Algorithm (C++-based):
g++ (GNU Compiler Collection) or

Visual Studio Code with C++ extension

3. Run in Simulator
Navigate to the /simulator folder and follow the steps in README.md. Use an open-source simulator like CARLA or DonkeyCar to load test scenarios and visualize the vehicle's pathfinding without lane data.

4. Deploy to Prototype
Refer to /prototype/setup.md for Raspberry Pi setup. Ensure the following are connected:

Front-facing camera (USB or PiCam)

Motor controller (e.g., L298N)

Power source
Run the main program to begin real-world testing.

🤝 Contributions
Contributions are welcome!

Open an issue to propose a feature or bug fix

Fork the repo and submit a pull request after discussion

🛡 License
This project is licensed under the MIT License.
Use is intended for educational and academic purposes only.

