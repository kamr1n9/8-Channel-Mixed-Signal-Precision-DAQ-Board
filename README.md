# 8-Channel-Mixed-Signal-Precision-DAQ-Board
Custom 8-channel mixed-signal DAQ board for measuring 0–3.3 V, 0–10 V, and differential analog signals. It uses protected analog frontends, RC filters, op-amp buffers, a 24-bit ADS131M08 ADC, and an STM32 to stream data to a PC for logging and visualization.
## Project Overview

This project is an 8-channel precision DAQ system for sensor measurement, embedded testing, and signal monitoring applications.

The board supports:

- 4x 0–3.3 V sensor input channels
- 2x 0–10 V industrial-style input channels
- 2x differential precision input channels
- 24-bit simultaneous-sampling ADC
- STM32-based digital control
- USB-C power and data interface
- SPI communication between ADC and MCU
- Python dashboard and data logging

## System Architecture
