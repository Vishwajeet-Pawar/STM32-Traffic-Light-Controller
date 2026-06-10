STM32 Traffic Light Controller

A simple but professional Traffic Light Controller project using  STM32F103C6T6  microcontroller. Built for learning and portfolio purposes.

 Features
- Red → Yellow → Green → Yellow sequence
- Timing: 5s Red, 2s Yellow, 5s Green, 2s Yellow
- Active-Low LED configuration
- Fully simulated in Proteus
- Clean code using STM32 HAL

 Project Structure
STM32_Source_Code → Complete STM32CubeIDE project
Proteus_Simulation → Simulation files
Images  → Screenshots and circuit diagrams

Hardware Used
- STM32F103C6T6A
- LEDs (Red, Yellow, Green) on PA0, PA1, PA2
- 220Ω resistors

 How to Run
1. Open project in STM32CubeIDE
2. Build and flash to STM32
3. Or run simulation in Proteus

 Future Enhancements
- Pedestrian crossing button
- Finite State Machine (FSM)
- Timer-based timing (no HAL_Delay)
- UART debugging


