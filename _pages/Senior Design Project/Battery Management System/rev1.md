---
title: "BMS PCB Revision #1 (In Progress)"
date: "2025-12-13"
thumbnail: "/assets/img/Senior Design Photos/Senior_Design_PCB_3D_photo.png"
---

# Project Description 
---
The Battery Management System (BMS) PCB is the primary board for our senior design project: a 10S battery monitoring system for ten 3.3 V cells connected in series. Our goal is to develop a flexible, load-agnostic BMS that can support a wide range of attached devices—especially high-power computing platforms running AI workloads, which are known for large and dynamic current draw.

The board integrates key safety features, including per-cell voltage monitoring, temperature monitoring, and controlled charge/discharge protection. It uses the TI BQ76930 battery monitor IC to measure cell voltages and manage protection functions, while an STM32 microcontroller provides higher-level control and communication. The STM32 connects to a laptop over USB-C for configuration, data logging, and status display. 

![](/NP-Portfolio/assets/img/Senior Design Photos/Senior_Design_PCB_2D_photo.png)

# Revisions 
- Test points were added for more efficient board testing
- Missing reset button
- Excessive copper pours replaced with trace
- Fixed stitching errors
- Compensated board to avoid using blinds (expensive)

# Schematics 
---
[1] Top_Level.SchDoc
![](/NP-Portfolio/assets/img/Senior Design Photos/Schem_1_photo.png)
[2] Connectors.SchDoc
![](/NP-Portfolio/assets/img/Senior Design Photos/Schem_2_photo.png)
[3] BQ76930.SchDoc
![](/NP-Portfolio/assets/img/Senior Design Photos/Schem_3_photo.png)
[4] HW-Temp-Mon.SchDoc
![](/NP-Portfolio/assets/img/Senior Design Photos/Schem_4_photo.png)
[5] Power-Tree.SchDoc
![](/NP-Portfolio/assets/img/Senior Design Photos/Schem_5_photo.png)
[6] STM32F3.SchDoc
![](/NP-Portfolio/assets/img/Senior Design Photos/Schem_6_photo.png)
[7] Fan-Controls.SchDoc
![](/NP-Portfolio/assets/img/Senior Design Photos/Schem_7_photo.png)

# 3D Model
---
![](/NP-Portfolio/assets/img/Senior Design Photos/Senior_Design_PCB_3D_photo.png)
