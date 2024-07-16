# Custom-STM32F3-Board

![image](https://github.com/user-attachments/assets/ec95a244-d1b9-4930-9126-285d0cec98e3)
![image](https://github.com/user-attachments/assets/7cf004de-c664-4a32-91fc-ad47f582675a)
![image](https://github.com/user-attachments/assets/b48a7ec6-cc29-4db0-aebb-2fa4e9590ef0)



# Custom PCB Project with STM32F103C8T6

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Project Overview

This project focuses on designing a custom 2 layer PCB powered by the STM32F103C8T6 ARM chip. It features RS232, USB, 2xADC, and 4xDAC headers. The remaining pins are configurable as GPIO.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Opening the Project](#opening-the-project)
  - [Design Workflow](#design-workflow)
- [Programming](#programming)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This repository includes all necessary files and documentation to design a custom STM32 M3 PCB using Altium Designer. It ensures a robust and efficient PCB layout with custom components and libraries.

## Features

- **STM32F103C8T6 ARM chip**: Provides a powerful and flexible microcontroller core.
- **RS232 Interface**: For serial communication.
- **USB Interface**: For easy connectivity and data transfer.
- **2x ADC (Analog-to-Digital Converters)**: For analog signal processing.
- **4x DAC (Digital-to-Analog Converters)**: For generating analog signals.
- **Configurable GPIO Pins**: The rest of the pins are configurable as General Purpose Input/Output.

## Getting Started

### Prerequisites

- [Altium Designer](https://www.altium.com/) installed on your computer.
- Basic knowledge of PCB design and Altium Designer.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/custom-pcb-project.git
    cd custom-pcb-project
    ```

2. Open the project in Altium Designer:
    - Launch Altium Designer.
    - Open the `.PrjPcb` project file.

## Usage

### Opening the Project

1. Open Altium Designer.
2. Navigate to `File > Open Project`.
3. Select the `.PrjPcb` file from the cloned repository.

### Design Workflow

1. **Schematic Design**: Modify or add components in the schematic.
2. **PCB Layout**: Arrange the components on the PCB layout.
3. **Routing**: Connect the components with traces.
4. **Validation**: Run design rule checks to ensure the design meets all requirements.
5. **Fabrication Outputs**: Generate Gerber files and other outputs for manufacturing.

## Programming
To program the board, an ST-LINK will be enough to flash via SWD.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with detailed descriptions of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Thanks to the contributors and the Altium Designer community for their support and resources.




