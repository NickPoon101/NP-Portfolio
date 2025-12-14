---
title: "Accumulator Management Board"
date: "2025-05-31"
thumbnail: "/assets/img/AMB HR FSAE photos/AMB_PCB_3D_photo.png"
---

# Project Description 
---
The Accumulator Management Board, aka Watchdog, is a precharge circuit that separates the main tractive system of the FSAE vehicle from the accumulator. Utilizing an AIR (Accumulator Isolation Relay) to isolate the accumulator from the main system, we time a switching circuit to control the charging current coming from the 400V accumulator. By breaking and closing the circuit through the precharge resistor, we can safely charge the precharge capacitor and connect to the system. This design is analog-controlled and doesn't use digital voltage readings to control the switching. Other applications include a stepdown circuit from the 400V input to a 12V output to power the low-voltage circuitry.

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
