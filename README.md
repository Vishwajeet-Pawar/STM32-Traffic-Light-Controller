# 🚦 STM32 Traffic Light Controller

A clean and professional **Traffic Light Controller** project using **STM32F103C6T6** microcontroller. Built for Embedded Systems learning and job portfolio.

## ✨ Features
- Standard traffic light sequence: **Red → Yellow → Green → Yellow**
- Timing: Red (5s), Yellow (2s), Green (5s), Yellow (2s)
- Active-Low LED configuration
- Developed using **STM32CubeIDE** + **HAL Library**
- Fully simulated in **Proteus**

## 📁 Project Structure
- **STM32_Source_Code.zip** → Complete STM32CubeIDE project (extract and open)
- **Proteus_Simulation/** → Simulation file
- **Images/** → Project screenshots and diagrams

## 🛠 Hardware
- **MCU**: STM32F103C6T6A
- **LED Connections** (Active Low):
  - PA0 → Red LED
  - PA1 → Yellow LED
  - PA2 → Green LED

## 🚀 How to Run
1. Download and extract `STM32_Source_Code.zip`
2. Open the project in **STM32CubeIDE**
3. Build the project
4. Run simulation in Proteus

## 📸 Screenshots
### Proteus Simulation
![Red LED ON](Images/Red%20LED.png)
![Yellow LED ON](Images/Yellow%20LED.png)
![Green LED ON](Images/Green%20LED.png)

### Code & Configuration
![GPIO Configuration](Images/IOC%20file.png)
![while(1) Loop](Images/while(1)%20-%20Code.png)
![Function Declaration](Images/Function%20Declaration.png)
![Function Calling](Images/Function%20Calling.png)

## 🔮 Future Enhancements (Planned)
- Pedestrian crossing button
- Finite State Machine (FSM) implementation
- Timer interrupt based timing (remove HAL_Delay)
- UART debugging output

---

**Made with ❤️ for Embedded Systems Portfolio**
