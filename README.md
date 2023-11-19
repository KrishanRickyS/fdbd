# Intruder Detection System

## Abstract

This project presents an Arduino-based Intruder Detection System designed to enhance security measures. The system employs an ultrasonic sensor for intruder detection and incorporates various components for comprehensive alerting. In the absence of an internet connection, the system utilizes a GSM module for sending SMS alerts, ensuring reliable notifications in any scenario. The integration of a Telegram bot allows real-time alert messages with accompanying images, providing a robust security solution for diverse environments.

## Components

1. **Arduino Board (1N)**
2. **Ultrasonic Sensor (1N)**
3. **GSM Module (1N)**
4. **Centre Shaft Geared Motor (1N)**
5. **ESP-32 CAM (1N)**
6. **LCD Display (1N)**
7. **Buzzer (1N)**
8. **Jumper Wires**

## Working

The Intruder Detection System operates as follows:

1. **Intruder Detection:**
   - The ultrasonic sensor detects any intruder within its range.

2. **Alert Generation:**
   - Upon detection, the system triggers an alert.

3. **Telegram Alert (With Internet):**
   - If an internet connection is available, a Telegram bot sends a real-time alert message along with an image capture.

4. **SMS Alert (Without Internet):**
   - In the absence of internet connectivity, the GSM module sends an SMS alert to predefined numbers.

5. **Motor Activation (Optional):**
   - Optionally, the system can activate a geared motor or other response mechanisms.

6. **LCD Display and Buzzer Feedback:**
   - The LCD display provides a visual indication of the system status, and a buzzer can be used for audible alerts.

## Installation

[Include installation instructions, dependencies, and any configuration steps needed for the project.]

## Usage

[Provide examples and instructions on how to use the Intruder Detection System.]

## Contributing

[Include guidelines for contributing to the project if applicable.]

## License

[Specify the license under which the Intruder Detection System is distributed.]

## Contact Information

[Provide contact information for questions or feedback.]

## Acknowledgments

[Give credit to any third-party libraries, tools, or individuals that contributed to the project.]
