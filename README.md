# ♻️ Plastic Bottle to 3D Filament Machine – RAMPS 1.4 Controller

## 🧩 Project Overview

This project implements firmware-level control for a machine that recycles plastic bottles into 3D printer filament. It uses the **RAMPS 1.4 control board**, and the firmware is built on **Marlin** with EEPROM support and motion control for the X-axis motor.

The machine performs:
- **Plastic extrusion**
- **Filament diameter control**
- **X-axis motor management for filament pulling or winding**
- EEPROM storage and retrieval of settings

---

## 🛠️ Hardware Components
![Alt text](Circuit.png)
- 🧠 **RAMPS 1.4** controller board
- 🔥 **Heated extruder**
- ⚙️ **Stepper motor (X-axis)** for filament movement
- 🧪 **Temperature sensor (thermistor)**
- 💾 **EEPROM** for persistent configuration
- ⛓️ **Custom bottle feeding system**
- 🧵 **Filament winding system**

---

## 📁 File Description

**`Marlin_EEPROM_Config_RAMPS14_XAxisControl.cpp`**  
> This file contains EEPROM handling, motor configuration for the X-axis, and PID temperature control. It defines default machine behavior, saves settings across reboots, and enables motion planning using the RAMPS 1.4 pinout.

---


