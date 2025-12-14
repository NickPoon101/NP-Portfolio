---
title: "Accumulator Management Board"
date: "2025-05-31"
tags: [EE, High Voltage, Embedded, Power Circuit, PCB]
thumbnail: "/assets/img/AMB HR FSAE photos/AMB_PCB_3D_photo.png"
---

# Project Description 
---
The Accumulator Management Board (AMB), also known as the “Watchdog,” is an analog precharge and protection board that isolates the FSAE vehicle’s main tractive system from the high-voltage accumulator. It uses an Accumulator Isolation Relay (AIR) to keep the accumulator disconnected from the tractive system until precharge is complete.

During startup, a timed switching circuit routes current through a precharge resistor to safely charge the DC-link (precharge) capacitor, limiting inrush current. Once the capacitor is charged, the circuit closes to connect the accumulator to the rest of the system. This design is fully analog-controlled and does not rely on digital voltage sensing for switching decisions.

The board also includes a 400 V to 12 V step-down supply to power the vehicle’s low-voltage electronics.

![](/NP-Portfolio/assets/img/AMB HR FSAE photos/AMB_PCB_2D_photo.png)

# Revisions 
- Test points were added for more efficient board testing
- Switched from a digital system with STM32 to avoid coding applications
- Exchanged opctocoupler a few times because of faulty components
- Added LED indicators for the AIR connectors
  
# Schematics 
---

[1] HV_Precharge_Check.SchDoc
![](/NP-Portfolio/assets/img/AMB HR FSAE photos/Schem_1_photo.png)
[2] SDC_Logic.SchDoc
![](/NP-Portfolio/assets/img/AMB HR FSAE photos/Schem_2_photo.png)
[3] 12v_Stepdown.SchDoc
![](/NP-Portfolio/assets/img/AMB HR FSAE photos/Schem_3_photo.png)
[4] Connectors.SchDoc
![](/NP-Portfolio/assets/img/AMB HR FSAE photos/Schem_4_photo.png)
[5] GLV_Stepdown.SchDoc
![](/NP-Portfolio/assets/img/AMB HR FSAE photos/Schem_5_photo.png)

# 3D Model
---
![](/NP-Portfolio/assets/img/AMB HR FSAE photos/AMB_PCB_3D_photo.png)
