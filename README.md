# 🧪 STM32F1 Project Assignments

This repository contains STM32-based embedded systems (schematic only) where the designs will be based. Each student has a unique sensor module to interface with an STM32 microcontroller, applying sensor integration, and system design skills.

## 📋 The Projects

| No. | First Name | Last Name     | Project Description         | Components Used         |
|-----|------------|---------------|-----------------------------|--------------------------|
| 1   | Amoreld    | Mija          | Weather Station             | STM32 + SHT30            |
| 2   | Andi       | Sula          | IR Receiver Decoder         | STM32 + TSOP38238        |
| 3   | Ardit      | Kollçaku      | Motor Driver                | STM32 + L9110            |
| 4   | Arli       | Mali          | Tilt Sensor                 | STM32 + MPU6050          |
| 5   | Aron       | Bazini        | Pressure Sensor             | STM32 + BMP388           |
| 6   | Dario      | Dona          | Pulse Oximeter              | STM32 + MAX30100         |
| 7   | Enea       | Polo          | Ultrasonic Distance Sensor  | STM32 + HC-SR04          |
| 8   | Fabian     | Muka          | Accelerometer               | STM32 + ADXL345          |
| 9   | Fabio      | Kurti         | Environment Sensor          | STM32 + BME280           |
| 10  | Fabio      | Agalliu       | Lidar Sensor                | STM32 + VL53L0X          |
| 11  | Henrik     | Krosi         | Proximity Sensor            | STM32 + APDS9960         |
| 12  | Ibrahim    | Bali          | Environment Sensor          | STM32 + BME280           |
| 13  | Lorna      | Qoku          | Analog Temperature Sensor   | STM32 + LM35             |
| 14  | Marjos     | Kopaçi        | Accelerometer               | STM32 + ADXL345          |
| 15  | Oresti     | Elezi         | Air Quality Sensor          | STM32 + CCS811           |
| 16  | Sedion     | Çuçi          | Light Sensor                | STM32 + TSL2561          |
| 17  | Xhensila   | Lasku         | Proximity Sensor            | STM32 + APDS9960         |

## 🛠️ Tools & Technologies

- **Microcontroller**: STM32F103C8T6TR
- **Platforms to use**: STM32CubeIDE, Kicad V6+
- **Communication**: I2C, SPI, UART (varies per sensor)

  Each student must follow these steps to complete their project:

1. 🔧 **Schematic Reference**
   - Open the folder for your assigned project.
   - Review the provided schematic diagram.
   - Use only the sensor in the schematic and connect it to the STM32 following the correct interface protocol (I2C, SPI, or analog/digital).

2. 🧩 **Library Setup**
   - Inside each project folder is a symbol and footprint for the sensor.
   - Import these into your PCB design software (e.g., KiCad or Altium).

3. 🖼️ **Schematic Design**
   - Create your own schematic based on the reference using the provided symbol.
   - Do not add extra components—only the sensor and STM32 connections are needed.

4. 🖥️ **PCB Design**
   - Convert your schematic to a PCB layout.
   - Follow the board stackup requirement based on your project (2-layer or 4-layer):

     **4-Layer Stackup:**
     - Top: Signal  
     - Layer 2: VCC  
     - Layer 3: GND
     - Bottom: Signal  

     **2-Layer Stackup:**
     - Top: Signal  
     - Bottom: GND

5. 📏 **Design Rules**
   - VCC traces: **0.3 mm**
   - Signal traces: **0.15 mm**
   - Via: **0.6 mm/0.3 mm**

## ✅ Objectives

- STM32 MCUs to sensor interfacing
- Build and demonstrate a working embedded project
