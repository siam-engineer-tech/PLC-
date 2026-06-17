# Project Name: Metal Detection System Using Siemens PLC

# Project Overview

The **Metal Detection System Using Siemens PLC** project is designed to automatically detect metallic objects using an inductive proximity sensor (metal sensor). The PLC continuously monitors the sensor input and activates an output device whenever a metal object is detected.

This project demonstrates the practical application of PLC-based industrial automation for metal detection, object sensing, and process control.

---

# Objectives

- Detect metal objects automatically
- Learn Siemens PLC programming
- Understand inductive proximity sensor operation
- Interface sensors with PLC
- Improve industrial automation knowledge
- Understand Ladder Logic programming

---

# Features

- Automatic Metal Detection
- Non-Contact Sensing
- Metal Presence Indicator
- Fast Detection Response
- Industrial PLC Programming
- Reliable Operation
- Easy to Modify
- Suitable for Conveyor Automation

---

# Theory

A **Programmable Logic Controller (PLC)** is an industrial digital controller used to automate machines and manufacturing processes.

In this project, an **Inductive Proximity Sensor (Metal Sensor)** is connected to the Siemens PLC. The sensor generates a digital signal whenever a metallic object enters its sensing range. The PLC reads this input signal and energizes an output such as an indicator lamp, buzzer, or relay.

The PLC continuously scans the input devices, executes the ladder logic program, and updates the outputs during every scan cycle.

---

# Input / Output List

## Digital Inputs

| Address | Device | Type | Description |
|----------|--------|------|-------------|
| I1 | Metal Sensor (Inductive Proximity Sensor) | NO | Detects metal objects |

---

## Digital Outputs

| Address | Device | Description |
|----------|--------|-------------|
| Q1 | Green Indicator Lamp | Turns ON when metal is detected |
| Q2 | Buzzer | Sounds when metal is detected |
| Q3 | Red Indicator Lamp | Indicates no metal detected |

---

# Components Used

| Component | Quantity |
|-----------|---------:|
| Siemens PLC | 1 |
| Inductive Proximity Sensor (Metal Sensor) | 1 |
| Green Indicator Lamp | 1 |
| Red Indicator Lamp | 1 |
| Buzzer | 1 |
| 24V DC Power Supply | 1 |
| MCB (Miniature Circuit Breaker) | 1 |
| Connecting Wires | As Required |
| Terminal Blocks | As Required |

---

# Working Principle

1. Power ON the Siemens PLC.
2. PLC continuously scans the metal sensor input.
3. When a metal object enters the sensing range:
   - The metal sensor detects the object.
   - PLC receives a HIGH signal at input **I1**.
4. The PLC energizes the output **Q1**.
5. The Green Indicator Lamp turns ON.
6. The Buzzer connected to **Q2** also turns ON.
7. When the metal object is removed:
   - Sensor output becomes LOW.
   - PLC turns OFF all outputs.
8. The system returns to standby mode and waits for the next detection.

---


---

# Ladder Diagram

Download the Ladder Diagram:

[Metal Detection System](../Circuit%20Diagram/ladder%20code/Metal%20sensor%20using%20PLC.lld)


---

# Applications

- Conveyor Belt Metal Detection
- Automatic Sorting Systems
- Manufacturing Industry
- Packaging Industry
- Automobile Industry
- Food Processing Plants
- Material Handling Systems
- Industrial Automation

---

# Advantages

- Non-contact sensing
- Fast response
- High reliability
- Easy installation
- Low maintenance
- Industrial standard
- High detection accuracy

---

# Limitations

- Detects only metallic objects
- Limited sensing distance
- Detection range depends on metal type
- Requires proper alignment

---

# Future Improvements

- Metal Object Counter
- HMI Interface
- SCADA Monitoring
- Conveyor Belt Automation
- Automatic Metal Sorting
- IoT Monitoring
- Cloud Data Logging
- Remote Monitoring

---

# Testing

| Test | Result |
|------|--------|
| Metal Detection | ✅ Pass |
| Green Indicator Lamp | ✅ Pass |
| Red Indicator Lamp | ✅ Pass |
| Buzzer Operation | ✅ Pass |
| PLC Communication | ✅ Pass |

---

# Skills Demonstrated

- Siemens PLC Programming
- Ladder Logic Programming
- Industrial Automation
- Sensor Integration
- Metal Detection System Design
- Electrical Wiring
- Industrial Troubleshooting
- Git & GitHub Documentation

---

# Author

**Md. Shahibul Hasan Siam**

B.Sc. in Electrical and Computer Engineering  
Rajshahi University of Engineering and Technology (RUET)

PLC & Industrial Automation Enthusiast

Bangladesh

---