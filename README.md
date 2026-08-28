# TÜBİTAK 2209-A: Advanced Solar Energy Management System with SEPIC Converter & MPPT Control

[![TÜBİTAK 2209-A](https://img.shields.io/badge/T%C3%9CB%C4%B0TAK-2209A%20Supported-blue.svg)](https://www.tubitak.gov.tr)
[![Power Electronics](https://img.shields.io/badge/Domain-Power%20Electronics%20&%20Hardware-orange.svg)]()
[![Altium Designer](https://img.shields.io/badge/PCB-Altium%20Designer-green.svg)]()

---

## Project Overview
This repository contains the comprehensive hardware design, schematic capture, and PCB layout files for an advanced solar energy harvesting and management system. Developed under the **TÜBİTAK 2209-A University Students Research Projects Support Program**, this project focuses on maximizing photovoltaic (PV) panel efficiency through a non-isolated DC-DC power converter topology coupled with an intelligent Maximum Power Point Tracking (MPPT) algorithm.

The system is engineered to bridge variable solar irradiance conditions with stable battery storage requirements, providing a robust, high-efficiency power conversion stage tailored for renewable energy applications.

---

## Technical Specifications & Topology Architecture

* **Converter Topology:** Single-Ended Primary-Inductor Converter (**SEPIC**), capable of stepping up or stepping down voltage seamlessly depending on the solar panel's operating point relative to the battery voltage.
* **Inductor Design:** Utilizes a custom-configured **coupled inductor** architecture to minimize input current ripple, reduce magnetic component volume, and enhance overall power density.
* **Control Algorithm:** Implements the **Perturb & Observe (P&O)** Maximum Power Point Tracking (MPPT) algorithm to dynamically adjust the duty cycle and track the maximum power locus under fluctuating environmental conditions.
* **Hardware & EDA Tools:** 
  * Schematic capture and multi-layer PCB layout designed using **Altium Designer**.
  * Power stage modeling and circuit simulation performed via power electronics tools.

---

### 3. Manufactured Hardware & Prototype Testing Setup

<img width="1599" height="899" alt="TUBITAK-2209A-SEPIC-MPPT-Converter" src="https://github.com/user-attachments/assets/04283d1e-c5e4-4808-9422-0a7b009b5c69" />


* **Test Bench & Equipment:** The fully assembled PCB prototype is integrated into a complete laboratory test setup, operating alongside a digital multimeter, DC power supply, oscilloscope, and load resistor.
* **Hardware Realization:** Displays the physical deployment of the SEPIC converter circuit, coupled inductor, microcontroller control board, and power components working seamlessly together under real operating conditions.
