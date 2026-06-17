# Project Name: Automatic Motor ON/OFF Using PLC


# Project Overview

The **Automatic Motor ON/OFF Using PLC** project is designed to automate the operation of an electric motor based on input conditions. The PLC continuously monitors the connected input devices and controls the motor automatically without requiring manual intervention.

This project demonstrates the basic concepts of industrial automation using PLC Ladder Logic.

---

# Objectives

- Automate motor operation
- Reduce manual work
- Improve safety
- Increase system reliability
- Learn PLC programming
- Understand Ladder Logic programming

---

# Features

- Automatic Motor ON
- Automatic Motor OFF
- Start Button
- Stop Button
- Motor Status Indicator
- Emergency Stop Support
- Industrial PLC Programming
- Easy to Modify

---

# Theory

A **Programmable Logic Controller (PLC)** is an industrial digital computer used to control machinery and automation processes.

In this project, the PLC receives signals from the Start and Stop push buttons. When the Start button is pressed, the PLC energizes the output coil connected to the motor contactor, turning the motor ON. When the Stop button is pressed, the PLC de-energizes the output coil, stopping the motor.

The PLC continuously scans all inputs, executes the ladder logic program, and updates the outputs in every scan cycle.

---

# input / Output List

## Digital Inputs

| Address | Device | Type | Description |
|----------|--------|------|-------------|
| I1 | ON Push Button | NO | Starts the motor |
| I2 | OFF Push Button | NC | Stops the motor |
| I3 | Overload Relay (O/L) | NC | Protects the motor from overload |

---

## Digital Outputs

| Address | Device | Description |
|----------|--------|-------------|
| Q1 | Motor Contactor | Controls the motor |
| Q2 | Active Indicator (Green Lamp) | Indicates motor is running |
| Q3 | Deactive Indicator (Red Lamp) | Indicates motor is stopped |

---

# Components Used

| Component | Quantity |
|-----------|---------:|
| PLC (Programmable Logic Controller) | 1 |
| Start Push Button (NO) | 1 |
| Stop Push Button (NC) | 1 |
| Overload Relay (NC Contact) | 1 |
| Motor Contactor | 1 |
| Three-Phase Induction Motor | 1 |
| Green Indicator Lamp | 1 |
| Red Indicator Lamp | 1 |
| MCB (Miniature Circuit Breaker) | 1 |
| 24V DC Power Supply (for PLC) | 1 |
| Connecting Wires | As Required |
| Terminal Blocks | As Required |

---

#  Working Principle

1. Power ON the PLC.
2. PLC scans all input devices.
3. If the Start button is pressed:
   - Motor turns ON.
4. Motor remains ON using a holding (seal-in) circuit.
5. If the Stop button is pressed:
   - Motor turns OFF.
6. PLC waits for the next command.

---

# System Overview

```
+----------------+
| Start Button   |
+----------------+
        |
        v
+----------------+
|      PLC       |
+----------------+
        |
        v
+----------------+
| Motor Contactor|
+----------------+
        |
        v
+----------------+
| Electric Motor |
+----------------+
```

---



# Circuit Diagram

Below is the circuit diagram for the motor On and off  using PLC control system:

![automatic water pump]( ../Images/motor_on_off.png)

# Ladder Diagram

Download the Ladder diagram:
[Automatic motor On off system]( ../Circuit%20Diagram/ladder%20code/Motor%20On%20%20&%20OFF%20with%20signal%20lamps.lld)

# Applications

- Industrial Motor Control
- Water Pump Control
- Conveyor System
- Fan Control
- Compressor
- Production Line
- Manufacturing Plant
- Agriculture Automation

---

# Advantages

- Easy to operate
- Reliable
- Low maintenance
- Industrial standard
- Flexible programming
- High safety
- Easy troubleshooting

---

# Limitations

- Requires PLC hardware
- Higher initial cost
- Needs programming knowledge
- Dependent on power supply

---

# Future Improvements

- HMI Interface
- SCADA Monitoring
- IoT Integration
- GSM Notification
- VFD Speed Control
- Cloud Monitoring
- Remote Access

---

#  Testing

| Test | Result |
|------|--------|
| Start Button | ✅ Pass |
| Stop Button | ✅ Pass |
| Motor ON | ✅ Pass |
| Motor OFF | ✅ Pass |
| Indicator Lamp | ✅ Pass |

---



# Skills Demonstrated

- PLC Programming
- Ladder Logic
- Industrial Automation
- Motor Control
- Electrical Wiring
- Industrial Troubleshooting
- Automation Design
- Git & GitHub Documentation

---

# Author

**Md. Shahibul Hasan Siam**

B.Sc. in Electrical and Computer Engineering
Rajshahi University Of Engineering and technology(Ruet)

PLC & Industrial Automation Enthusiast

Bangladesh

---
