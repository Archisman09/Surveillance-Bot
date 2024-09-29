## Surveillance Semi-Autonomous Bot using ESP32 CAM

This repository contains the code for a semi-autonomous surveillance bot powered by an ESP32 CAM module. The bot utilizes real-time video streaming and can perform autonomous movements based on sensor inputs.

## Files Included

1. **Main Sketch File (.ino)**:
   - The core of the project, which controls the ESP32 CAM module, handles video streaming, and manages autonomous movement algorithms.

2. **Header File (.h)**:
   - Contains function declarations, global variables, and configurations for various functionalities of the bot.

3. **CPP File (.cpp)**:
   - Contains the implementation of functions defined in the header file. This file handles more complex tasks, such as data processing and communication with other components of the system.

## Features

- **Real-time Video Streaming**: The ESP32 CAM provides a live video feed, which can be accessed via the web interface.
- **Autonomous Movement**: The bot uses sensor data to navigate semi-autonomously in its environment.
- **Remote Control**: Through a web interface, the user can manually override the bot's movement.

## Getting Started

### Requirements

- ESP32 CAM Module
- Arduino IDE
- CameraWebServer library
- Other required components like motor drivers, sensors, and power supplies.

### Installation

1. Clone the repository:
   git clone https://github.com/Archisman09/Surveillance-Bot.git

2. Open the `.ino` file in Arduino IDE.

3. Ensure that the header and cpp files are placed in the same directory as the `.ino` file or in a `src` folder.

4. Install required libraries using Arduino IDE’s library manager.

5. Upload the sketch to your ESP32 CAM.

### Usage

1. Connect the ESP32 CAM module to a power source and ensure it has network connectivity.
2. Access the video stream through the IP address displayed in the serial monitor.
3. Control the bot remotely through the web interface or let it run autonomously based on pre-defined movement algorithms.

## Contributing

Feel free to open issues or submit pull requests if you have any suggestions for improving the project.

---

Let me know if you need any modifications!
