
# 01-Blinky - STM32F103C8 Blue Pill Project

Welcome to the **01-Blinky** project! This project is a fundamental example of how to blink an LED using the STM32F103C8 microcontroller. It is an excellent starting point for understanding GPIO (General Purpose Input/Output) pin configuration and basic timing operations with the STM32 microcontroller.

## Project Overview

The 01-Blinky project demonstrates how to configure and control GPIO pins on the STM32F103C8 microcontroller to blink an LED at a regular interval. This example uses STM32 HAL (Hardware Abstraction Layer) and STM32CubeIDE for development.

### Project Structure

- **Firmware/**: Contains STM32CubeIDE project files.
- **Simulation/**: Contains Proteus simulation files to visualize the hardware behavior.
- **Images/**: Includes visual aids for understanding pin configurations and clock settings.

## Project Components

### Firmware

The `Firmware` directory includes:
- **STM32CubeIDE Project Files**: The source code and configuration files required to build and flash the Blinky application onto the STM32F103C8 microcontroller.

To get started with the firmware:
1. Open the STM32CubeIDE.
2. Import the project from the `Firmware` directory.
3. Build and upload the project to your STM32F103C8 microcontroller using ST-Link V2.

### Simulation

The `Simulation` directory contains:
- **Proteus Simulation File**: A virtual simulation of the Blinky project that shows how the LED blinks. This helps you visualize the hardware behavior without needing physical components.

To use the Proteus simulation:
1. Open the Proteus software.
2. Load the simulation file from the `Simulation` directory.
3. Run the simulation to observe the LED blinking behavior.

### Images

The `Images` directory contains useful diagrams and configuration images:
- **PINOUT-STM32F103C8.PNG**: Displays the pinout of the STM32F103C8 microcontroller. This helps identify the GPIO pins used in the project.
- **GPIO-setting.PNG**: Shows the GPIO pin settings configured for the Blinky project.
- **RCC-Clock-Config.PNG**: Illustrates the clock configuration settings used for the STM32F103C8 microcontroller.

## Getting Started

### Prerequisites

To work with this project, ensure you have:
- **STM32CubeIDE**: For project development and programming.
- **Proteus Software**: For simulating the hardware setup.
- **ST-Link V2**: For flashing and debugging the microcontroller.

### How to Build and Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/STM32F103C8-Blue-Pill-Projects.git
   cd STM32F103C8-Blue-Pill-Projects/01-Blinky
   ```

2. **Open the Project in STM32CubeIDE:**
   - Launch STM32CubeIDE.
   - Import the project from the `Firmware` directory.
   - Build the project.

3. **Flash the Firmware:**
   - Connect your STM32F103C8 microcontroller to your computer using ST-Link V2.
   - Upload the compiled firmware to the microcontroller.

4. **Run the Simulation (Optional):**
   - Open the Proteus software.
   - Load the simulation file from the `Simulation` directory.
   - Observe the LED blinking in the simulation environment.

## Troubleshooting

- **LED Not Blinking:** Ensure that the microcontroller is correctly connected and powered. Verify that the GPIO pin configuration matches your hardware setup.
- **Build Errors:** Check that all project dependencies are correctly configured in STM32CubeIDE.

## Contributing

Contributions are welcome! If you have improvements or suggestions, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
