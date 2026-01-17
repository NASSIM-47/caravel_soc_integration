

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

# Caravel SoC Integration – User Project

## 📌 Overview
This repository contains the design and integration of a **custom user hardware module** into the **Caravel System-on-Chip (SoC)** platform.  
The project follows a **complete ASIC design flow**, from **RTL design** to **physical layout generation**, using **OpenLane** and open-source EDA tools.


---

## 🎯 Project Objectives
- Design a **custom digital hardware module** using Verilog HDL  
- Integrate the module into the **Caravel SoC user area**
- Apply a **full ASIC flow (RTL → GDSII)**
- Perform **timing constraints, physical design, and verification**
- Gain hands-on experience with **SoC architecture and ASIC sign-off**

---

## 🧠 Project Description
The Caravel SoC provides a reference architecture that allows users to integrate their own hardware blocks inside a complete chip environment.

In this project:
- A **user project wrapper** was implemented
- The custom module was connected to the Caravel infrastructure
- The design was synthesized, placed, routed, and verified using **OpenLane**
- Physical verification steps such as **LVS** were performed
- Final layout files (**GDS**) were generated

---

## 🗂️ Repository Structure

---

## 🚀 How to Run OpenLane

This project uses **OpenLane** to perform a complete ASIC flow from **RTL to GDSII**.

### ✅ Prerequisites
- Linux environment
- Docker installed and running
- OpenLane properly installed
- Caravel environment set up

### 🔧 Running the Flow

1. Clone this repository:
2.git clone https://github.com/NASSIM-47/caravel_soc_integration.git
cd caravel_soc_integration 

---

## ⚙️ Tools & Technologies
- **HDL**: Verilog  
- **ASIC Flow**: OpenLane  
- **SoC Template**: Caravel  
- **EDA Tools**: OpenROAD, Magic, Netgen  
- **Technology**: Sky130 / CMOS  
- **Operating System**: Linux  

---

## ✅ Achievements
- Successful integration of a custom hardware block into a SoC
- Complete RTL-to-GDSII ASIC implementation
- Application of timing constraints and parasitic extraction
- Physical verification using LVS
- Strong understanding of **hardware architecture and SoC integration**


---


## 👤 Author
**Ammali Taieb Nassim**  
- LinkedIn: https://linkedin.com/in/taieb-nassim-ammali  
- GitHub: https://github.com/NASSIM-47  
- Email: ammali.t.nassim@gmail.com  

---

## 📄 License
This project is licensed under the **Apache-2.0 License**.




