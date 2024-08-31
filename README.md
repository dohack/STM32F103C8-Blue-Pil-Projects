
# STM32F103C8 Blue Pill Projects

Welcome to the **STM32F103C8 Blue Pill Projects** repository! This collection showcases various practical projects using the STM32F103C8 microcontroller, commonly known as the Blue Pill. Each project is designed to demonstrate different functionalities and peripherals of the STM32F103C8 using STM32 HAL (Hardware Abstraction Layer), STM32CubeIDE, STM32CubeMX, and other essential tools.

## 🚀 Introduction

The STM32F103C8 Blue Pill is a versatile microcontroller board based on the STM32F103C8T6 chip. It features a 32-bit ARM Cortex-M3 core and is suitable for a wide range of embedded applications. This repository contains a series of hands-on projects aimed at exploring various features and capabilities of the Blue Pill board. 

Each project includes a detailed description, hardware setup, and software implementation to help you learn and experiment with STM32 microcontrollers.

## 📦 Project Structure

The repository is organized into the following directories, each containing a specific project:

- **01-Blinky/**: A simple project to blink an LED on the Blue Pill board.
- **02-Push-Button/**: Demonstrates how to use a push button to control an LED.
- **02-Switch/**: Similar to the push button project, but with different switch types.
- **03-Analog-Potentiometer/**: Reads values from an analog potentiometer and displays them.
- **04-Seven-segment-display/**: Interfaces with a seven-segment display to show numeric values.
- **05-Lcd-16X2-segment/**: Interfaces with a 16x2 LCD display to show text.
- **06-Keypad-matrix/**: Implements a matrix keypad to capture user input.
- **07-Dc-motor/**: Controls a DC motor using PWM signals.
- **08-Servo-motor/**: Controls a servo motor to move to specified angles.
- **09-LM35-Temp-sensor/**: Reads temperature data from an LM35 sensor.
- **10-Relay-interfacing/**: Controls a relay to switch devices on and off.
- **11-RGB-interface/**: Interfaces with an RGB LED to create various colors.
- **12-Bluetooth-HC5/**: Communicates with a HC-05 Bluetooth module for wireless data exchange.
- **README.md**: This file with an overview of the repository and instructions.

## 🛠️ Tools and Equipment

To work on these projects, you will need the following tools and equipment:

- **STM32F103C8 Blue Pill Board**: The microcontroller development board.
- **STM32CubeIDE**: The integrated development environment for STM32 development.
- **STM32CubeMX**: The configuration tool for setting up the STM32 peripherals.
- **ST-Link V2**: The programmer and debugger for STM32 microcontrollers.
- **Breadboard**: For prototyping and connecting components.
- **Jumper Wires**: For making connections between the Blue Pill board and other components.
- **Various Modules and Sensors**: Depending on the project (e.g., LEDs, buttons, displays, motors, sensors, relays, Bluetooth modules).

## 📜 Project Details

### 01-Blinky

**Objective**: Blink an LED on the Blue Pill board to verify the setup.

**Hardware**: 
- Onboard LED connected to a specific GPIO pin.

**Software**:
- Initialize the GPIO pin as output.
- Toggle the LED state in a loop with a delay.

### 02-Push-Button

**Objective**: Use a push button to toggle an LED on and off.

**Hardware**:
- Push button connected to a GPIO pin.
- LED connected to another GPIO pin.

**Software**:
- Configure the push button pin as input.
- Configure the LED pin as output.
- Read the button state and toggle the LED accordingly.

### 02-Switch

**Objective**: Interface with different types of switches and control an LED.

**Hardware**:
- Various types of switches (e.g., toggle, slide).
- LED connected to a GPIO pin.

**Software**:
- Similar to the Push Button project but adapted for different switch types.

### 03-Analog-Potentiometer

**Objective**: Read analog values from a potentiometer and display them.

**Hardware**:
- Potentiometer connected to an analog input pin.

**Software**:
- Configure ADC (Analog-to-Digital Converter).
- Read and process the analog value from the potentiometer.

### 04-Seven-segment-display

**Objective**: Display numeric values on a seven-segment display.

**Hardware**:
- Seven-segment display connected to GPIO pins.

**Software**:
- Implement a driver for the seven-segment display.
- Write numeric values to be displayed.

### 05-Lcd-16X2-segment

**Objective**: Display text on a 16x2 LCD screen.

**Hardware**:
- 16x2 LCD connected via I2C or parallel interface.

**Software**:
- Configure the LCD driver.
- Write text strings to the display.

### 06-Keypad-matrix

**Objective**: Capture input from a matrix keypad.

**Hardware**:
- 4x4 matrix keypad connected to GPIO pins.

**Software**:
- Implement keypad scanning and decoding.

### 07-Dc-motor

**Objective**: Control the speed and direction of a DC motor using PWM.

**Hardware**:
- DC motor connected through a motor driver.

**Software**:
- Configure PWM for motor control.
- Implement functions for changing motor speed and direction.

### 08-Servo-motor

**Objective**: Control a servo motor to move to specific angles.

**Hardware**:
- Servo motor connected to a PWM output pin.

**Software**:
- Generate PWM signals to control the servo angle.

### 09-LM35-Temp-sensor

**Objective**: Measure temperature using an LM35 temperature sensor.

**Hardware**:
- LM35 temperature sensor connected to an analog input pin.

**Software**:
- Read analog values and convert them to temperature.

### 10-Relay-interfacing

**Objective**: Control a relay to switch devices on and off.

**Hardware**:
- Relay module connected to a GPIO pin.

**Software**:
- Implement relay control logic.

### 11-RGB-interface

**Objective**: Control an RGB LED to produce different colors.

**Hardware**:
- RGB LED connected to PWM-controlled GPIO pins.

**Software**:
- Implement color mixing by adjusting PWM signals.

### 12-Bluetooth-HC5

**Objective**: Communicate with a Bluetooth HC-05 module.

**Hardware**:
- HC-05 Bluetooth module connected via UART.

**Software**:
- Implement UART communication with the Bluetooth module.

## 🧑‍💻 Usage

Each project directory contains the source code, configuration files, and documentation specific to that project. Follow the instructions in each directory to build and run the project.

1. **Open STM32CubeIDE**: Import the project directory.
2. **Configure the Project**: Use STM32CubeMX for peripheral configuration if needed.
3. **Compile and Upload**: Build the project and upload it to the Blue Pill board using ST-Link V2.
4. **Test and Verify**: Follow the hardware setup instructions to test the project.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new project ideas, please fork the repository, make your changes, and create a pull request.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.