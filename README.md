# 5V to 3.3V LDO Voltage Regulator Module

## Overview
A compact, industry-standard Low Dropout (LDO) linear regulator module engineered to step down a 5V input to a stable 3.3V output for low-voltage microcontrollers and sensor peripherals.

This project focuses on industrial-grade schematic capture, component footprint management, tight 2D routing, and rigorous manufacturing validation using **Altium Designer Professional**.

## Key Features
* **Power Regulation:** Delivers a highly stable 3.3V output utilizing the MIC5317-3.3YM5-TR LDO.
* **Form Factor:** Extremely compact footprint designed for easy integration as a plug-in module using surface-mount connectors.
* **Manufacturing Validation:** Rigorously checked using Altium's Design Rule Verification and CAMtastic to ensure error-free fabrication files prior to manufacturing.

## Hardware Architecture & Stack
* **Core Component:** MIC5317-3.3YM5-TR (LDO Regulator)
* **Key Peripherals:** Surface-mount headers (SM02B-GHS-TB), 1uF decoupling capacitors.
* **PCB Design Tool:** Altium Designer Professional

## Design & Verification Workflow

### 1. Schematic Capture
*Logical design, net structuring, and component specification.*
![Schematic](Screenshot_2026-02-06_001751.png)

### 2. 2D Layout & Routing
*Trace routing, polygon pours, and silkscreen placement.*
![2D Layout](Screenshot_2026-02-06_001902.png)

### 3. 3D PCB Rendering
*Mechanical clearance and physical footprint verification.*
![3D Render Top](Screenshot_2026-02-06_002044.png)
![3D Render Bottom](Screenshot_2026-02-06_002009.png)

### 4. Manufacturing Validation
*Generating Design Rule Checks (DRC) and verifying CAM/Gerber outputs.*
![DRC Report](Screenshot_2026-02-06_001818.png)
![CAMtastic Viewer](Screenshot_2026-02-06_002232.png)

## Repository Contents
* **`/`** - Contains the native Altium project files (`.PrjPcb`, `.SchDoc`, `.PcbDoc`) for direct layout examination.
