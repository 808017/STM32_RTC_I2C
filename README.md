# STM32 RTC Module Interface using I2C and LCD

This project demonstrates interfacing a DS3231 Real-Time Clock (RTC) module with an STM32 microcontroller using the I2C protocol. The current date and time are displayed on a 16x2 LCD.

## Features

* DS3231 RTC communication via I2C
* Real-time display of Hours, Minutes, and Seconds
* Date display (Day, Month, Year)
* 16x2 LCD interface
* STM32CubeIDE project
* HAL library based implementation

## Hardware Used

* STM32 Development Board
* DS3231 RTC Module
* 16x2 LCD Display
* Potentiometer (10kΩ) for LCD contrast adjustment
* Connecting Wires
* Breadboard

## Software Used

* STM32CubeIDE
* STM32 HAL Library

## Connections

### DS3231 RTC Module

| DS3231 Pin | STM32 Pin   |
| ---------- | ----------- |
| VCC        | 3.3V / 5V   |
| GND        | GND         |
| SDA        | I2C SDA Pin |
| SCL        | I2C SCL Pin |

### 16x2 LCD

Configured in 4-bit mode.

## Project Structure

```
STM32_RTC_LCD
│
├── Core
│   ├── Inc
│   └── Src
├── Drivers
├── STM32_RTC_LCD.ioc
├── .project
├── .cproject
├── README.md
└── LICENSE
```

## Working Principle

1. STM32 initializes the I2C peripheral.
2. Current time and date are read from the DS3231 RTC module.
3. Data is converted into human-readable format.
4. Time and date are continuously displayed on the LCD.

## Example Output

```
TIME: 10:25:48
DATE: 13/06/2026
```

## Applications

* Digital Clock
* Data Logging Systems
* Industrial Automation
* Embedded Timing Applications
* Alarm and Scheduling Systems

## Author

**Yash Mane**

## License

This project is licensed under the MIT License.

This is my first Pull Request.
