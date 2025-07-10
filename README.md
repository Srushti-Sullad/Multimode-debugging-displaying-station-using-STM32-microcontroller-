# Multimode-debugging-displaying-station-using-STM32-microcontroller

📌 Project Overview
This project is a Multimode Debugging and Displaying Station designed using the STM32 microcontroller, integrating multiple modes of data display and control for testing embedded systems. It uses sensors, buttons, an OLED display, a GSM module, and an IoT platform to showcase real-time sensor data, remote alerts, and user interaction across different modes. It is especially useful for developers, testers, or hobbyists working with embedded hardware debugging or sensor interfacing.

🎯 Objective
To create a modular station that can:
Read environmental data via sensors.
Switch between different operation modes using buttons.
Display information locally (OLED) and remotely (via IoT or GSM).
Indicate system status with RGB LEDs.

⚙️ Key Components
STM32 Microcontroller (e.g., STM32F103) – Core controller managing logic and peripherals.
ESP32 Module – Provides Wi-Fi and IoT capabilities (Ubidots etc.).
GSM Module (e.g., A7670C) – Sends SMS alerts or notifications.
DHT11 Sensor – Captures temperature and humidity data.
OLED Display (I2C) – Displays sensor readings and system messages.
Push Buttons (3x) – Switch between multiple operational modes.
RGB LED – Indicates current operating mode with different colors.
IoT Platform (e.g., Ubidots) – Used to view data remotely or trigger actions.

💡 Features
Mode-based operation with real-time switching.
Local OLED and remote cloud display options.
GSM communication for internet-independent alerts.
Modular design for scalability and ease of testing.
RGB status indicator to easily identify active mode.

🌍 Real-Time Use Cases
Embedded system prototyping and testing.
Debugging stations in labs or workshops.
Remote weather stations for agricultural or urban areas.
Educational tool for learning multitasking and sensor interfacing.

🚀 Future Enhancements
Add voice command integration.
Implement data logging with SD card.
Use touch interface instead of physical buttons.
Add real-time clock (RTC) for timestamped data.
Expand to control actuators or perform predictive alerts via AI.
