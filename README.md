# 8-Channel Mixed-Signal Precision DAQ Board

Custom 8-channel mixed-signal data acquisition board for measuring 0–3.3 V, 0–10 V, and differential analog signals. The board includes protected analog frontends, precision filtering, op-amp buffering, a 24-bit ADS131M08 ADC, and an STM32F303 microcontroller for data acquisition and communication.

## Project Overview

This project is a complete embedded mixed-signal hardware system designed for sensor measurement, test equipment, and signal monitoring applications.

The board supports:

- 4x 0–3.3 V sensor inputs
- 2x 0–10 V analog inputs
- 2x differential precision inputs
- 24-bit simultaneous-sampling ADC
- STM32F303 microcontroller
- USB-C power and data
- UART debug interface
- SWD programming/debugging
- I2C expansion header
- CAN interface using SN65HVD230 transceiver
- 
## System Architecture
<img width="596" height="689" alt="image" src="https://github.com/user-attachments/assets/67aceefd-2fc7-4d99-855d-3deb5d36e35d" />
