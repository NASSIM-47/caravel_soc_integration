# Caravel User Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

# Caravel SoC Integration – User Project

## 📌 Overview
This repository contains the design and integration of a **custom user hardware module** into the **Caravel System-on-Chip (SoC)** platform.  
The project follows a **complete ASIC design flow**, from **RTL design** to **physical layout generation**, using **OpenLane** and open-source EDA tools.

This work was carried out in the context of a **Master’s Final Year Project (PFE)** in **Microelectronics**, in collaboration with the **CDTA (Centre de Développement des Technologies Avancées)**.

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



