# Automatic Water Pump Control System

This repository contains the complete project for automating a water pump control system using a PLC. The system is designed to control a water pump based on specific conditions like water level or pressure.

## Circuit Diagram

Below is the circuit diagram for the water pump control system:

![Water Pump Control Circuit](https://github.com/siam-engineer-tech/PLC-/blob/main/Images/automatic%20water%20pump%20using%20plc.png)


## PLC Ladder Diagram

The PLC ladder diagram for this system is designed to handle the automation of the water pump. The logic includes the following key components:
- **Water Level Sensor**: Detects the water level in the tank.
- **Pump Control Relay**: Turns the water pump on or off.
- **Timer**: Controls the pump's operation based on the water level.
  
## PLC Code

The PLC ladder logic code is implemented using Siemens PLCs and can be found in the raw file below.

### Download PLC Code

[Download PLC Code](https://github.com/siam-engineer-tech/PLC-/blob/main/Circuit%20Diagram/Automatic%20water%20pump%20control%20using%20PLC.lld)


## System Overview

- **Inputs**: Water level sensors
- **Outputs**: Water pump control, alarm system
- **Operation**: The system monitors the water level in the tank and automatically starts or stops the pump depending on predefined thresholds. If the water level is too low, the pump will turn on, and if it's too high, the pump will turn off.


