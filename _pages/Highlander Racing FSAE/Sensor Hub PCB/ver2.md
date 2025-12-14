---
title: "Sensor Hub Revision #2"
date: "2024-02-01"
tags: [EE, Embedded, ADC, CAN, PCB]
thumbnail: "/assets/img/SensorHub2_images/PCB_3D.png"
---

# Project Description 
---
The Sensor Hub PCB project is a board directed to facilitate system integration and conduct sensor fusion for all control sensors(Throttle Potentiometer, Steer, Brakes, etc.) on the vehicle. The board utilizes an STM32F-series microcontroller with a (CAN) BUS communication protocol design.

![](/NP-Portfolio/assets/img/SensorHub2_images/PCB_2D.png)

# Revisions 
- Test points were added for more efficient board testing
- Changed secondary connector to another Conn-Ampseal-776267-1
- Added LED indicators for the STM32 
- Reworked layout and validated circuitry in schematics
# Schematics 
---
Top_Level.SchDoc
![](/NP-Portfolio/assets/img/SensorHub2_images/Top_level.png)
[1] Connectors.SchDoc
![](/NP-Portfolio/assets/img/SensorHub2_images/Connectors.png)
[2] STM32F4.SchDoc
![](/NP-Portfolio/assets/img/SensorHub2_images/STM32F4.png)
[3] CAN_Transceiver.SchDoc
![](/NP-Portfolio/assets/img/SensorHub2_images/CAN_Tranceiver.png)
[4] Regulator.SchDoc
![](/NP-Portfolio/assets/img/SensorHub2_images/Regulators.png)
[5] Buzzer.SchDoc
![](/NP-Portfolio/assets/img/SensorHub2_images/Buzzer.png)

# 3D Model
---
![](/NP-Portfolio/assets/img/SensorHub2_images/PCB_3D.png)
