# 🚁 Helicopter Main Rotor Lab Prototype

## 📖 Overview

The Helicopter Main Rotor Lab Prototype is an experimental rotor propulsion test rig developed to study the basic principles of helicopter rotor aerodynamics, propulsion systems, motor control, and power management.

The project utilizes an 80 cm diameter fixed-pitch rotor driven by a high-torque Johnson DC motor and controlled through an ESP32-based Wi-Fi interface. The system serves as a laboratory-scale platform for investigating rotor thrust generation, torque effects, structural behavior, and electrical power consumption.

This prototype was developed as part of aerospace engineering laboratory experimentation and educational research.

![Images/Final Pic](https://github.com/sujeetsamal/Helicopter-Main-Rotor-Lab-Prototype/blob/b3e1eac60162c5e7944b8327e4dc11a91ef46c8a/Images/Final%20Pic)

---

## 🎯 Objectives

- Study helicopter rotor propulsion principles.
- Analyze rotor thrust generation.
- Investigate motor torque requirements.
- Demonstrate wireless motor control using ESP32.
- Evaluate battery-powered propulsion systems.
- Create a low-cost educational helicopter test platform.

---

## 🔧 System Specifications

| Parameter | Value |
|------------|------------|
| Rotor Diameter | 80 cm |
| Rotor Type | Fixed Pitch |
| Motor | Johnson DC Gear Motor |
| Motor Speed | 60 RPM |
| Motor Driver | L298N |
| Controller | ESP32 |
| Communication | Wi-Fi |
| Power Source | 3 × 3.7V Li-ion Cells |
| Voltage | 11.1V Nominal |
| Voltage Regulation | Buck Converter |
| Application | Educational Rotor Test Rig |

---

## ⚙️ Working Principle

The rotor is mounted on a rigid frame and powered by a high-torque DC motor. The ESP32 generates control signals that are sent to the L298N motor driver.

The motor driver regulates power delivery from the battery pack to the motor. As the motor rotates the main rotor, aerodynamic forces are generated on the rotor blades.

The setup allows observation of:

- Rotor lift generation
- Torque reaction
- Blade loading effects
- Motor current consumption
- Power transmission efficiency

---

## 🧩 Hardware Components

### Mechanical Components

- Main rotor assembly
- Rotor hub
- Rotor shaft
- Structural frame
- Mounting brackets

### Electrical Components

- ESP32 Development Board
- L298N Motor Driver
- Johnson Gear Motor (60 RPM)
- 3S Li-ion Battery Pack
- DC Buck Converter
- Power Switch
- Wiring Harness

---

## 📂 Project Structure

```
Helicopter-Main-Rotor-Lab-Prototype
│
├── Images
│   ├── CAD
│   ├── 2-D eng
│   ├── Internal Wires
│   ├── BMS WITH LI-ion
│   ├── Different angle
│   └── Final Pic
│
├── README.md
├── LICENSE
```

---

## 📸 Documentation

### CAD Model
Contains the 3D design and CAD representation of the rotor test rig.

### 2-D Engineering Drawing
Contains engineering drawings with dimensions and manufacturing references.

### Internal Wiring
Shows electrical connections between:
- ESP32
- L298N Driver
- Motor
- Battery Pack
- Buck Converter

### BMS With Li-ion
Illustrates battery management system connections and battery configuration.

### Different Angle
Photographs from multiple viewpoints for structural understanding.

### Final Picture
Completed assembled prototype.

---

## 🔋 Power System

The system is powered by three 3.7V Li-ion cells connected in series.

### Battery Configuration

```
3.7V + 3.7V + 3.7V
=
11.1V Nominal
```

A buck converter is used to provide regulated voltage to sensitive electronic components while maintaining safe operation.

---

## 🌐 ESP32 Wi-Fi Control

The ESP32 enables wireless control of the propulsion system.

Features:

- Wi-Fi connectivity
- Remote motor operation
- Low-cost implementation
- Expandable IoT architecture

Future versions may include:

- RPM monitoring
- Thrust measurement
- Telemetry logging
- Mobile app control
- Real-time data visualization

---

## 🧪 Experimental Applications

This prototype can be used for:

- Rotor aerodynamics experiments
- Propulsion system demonstrations
- Motor performance testing
- Aerospace laboratory exercises
- Student research projects
- Educational demonstrations

---

## 🚀 Future Improvements

- Variable pitch rotor mechanism
- Higher RPM brushless motor system
- RPM sensor integration
- Load cell based thrust measurement
- Data logging system
- Mobile application control
- Battery health monitoring
- Autonomous test sequences

---

## 👨‍💻 Author

**Sujeet Samal**

B.Tech Aerospace Engineering  
Centurion University of Technology and Management (CUTM)

---

## 📜 License

This project is released under the MIT License.

Feel free to use, modify, and distribute the project for educational and research purposes.
