
<h1 align="center">
<span style="color:#00CFFF;">Determining Dielectric Constant Using a Microstrip Ring Resonator</span><span style="color:#FF2D95;"></span>
</h1>

## 🔹 Overview
This experiment demonstrates a practical RF method for extracting the **dielectric constant (εr)** of a substrate and unknown materials using a **microstrip ring resonator**.

The approach is based on measuring **resonant frequency shifts** caused by the presence of a material under test (MUT).

---

## 🔹 Objectives
- Design a microstrip ring resonator (simulation: HFSS / CST)  
- Measure resonant frequencies and **quality factor (Q)**  
- Extract **effective dielectric constant (εeff)**  
- Determine **dielectric constant (εr)** of unknown materials  

---

## 🔹 Principle of Operation

A ring resonator exhibits resonance when its circumference equals an integer multiple of the guided wavelength.

- Resonant frequency depends on geometry and dielectric properties  
- Adding a material changes the electromagnetic field distribution  
- → Causes a measurable **frequency shift**

---

## 🔹 Experimental Setup

- Microstrip ring resonator (PCB)  
- Vector Network Analyzer (VNA)  
- RF cables + calibration kit  
- Material samples (unknown dielectric)  

---

## 🔹 Procedure

1. Calibrate the VNA  
2. Measure baseline resonance (no material)  
3. Place material on top of the resonator  
4. Measure shifted resonance frequency  
5. Compute:
   - Quality factor (Q)  
   - Effective dielectric constant (εeff)  
   - Material dielectric constant (εr)  

---

## 🔹 Observations

- Higher dielectric constant → lower resonant frequency  
- Stronger field confinement in higher ε materials  
- Coupling gap affects resonance visibility and Q  

---

## 🔹 Results

- Extracted εr of substrate  
- Extracted εr of unknown materials  
- Comparison:
  - Theory vs Simulation vs Measurement  

---

## 🔹 Applications

- RF material characterization  
- Antenna design  
- Microwave circuit validation  
- Wireless system development  

---

## 📷 Experiment Images

### 🔸 Ring Resonator Design
![Ring Resonator](../assets/images/ring_resonator_design.png)

### 🔸 Fabricated PCB
![PCB](../assets/images/ring_resonator_pcb.jpg)

### 🔸 Measurement Setup (VNA)
![Setup](../assets/images/ring_resonator_setup.jpg)

### 🔸 S-Parameters (S11 / S21)
![S-Parameters](../assets/images/ring_resonator_sparams.png)

### 🔸 Material Under Test
![Material](../assets/images/ring_resonator_material.jpg)

---

## 🧠 Notes

- Accuracy depends on calibration quality  
- Air gaps between material and resonator introduce errors  
- Lossy materials reduce Q-factor  

---
