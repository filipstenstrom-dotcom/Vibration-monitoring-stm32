# STM32-Based Vibration Monitoring System for SHM

This project aims to build a complete measurement and analysis system for Structural Health Monitoring (SHM) using an STM32 Nucleo-H753ZI, high-performance MEMS accelerometers (EVAL-ADXL355Z), and a Sensirion SHT40 temperature/humidity sensor.  
The system measures the vibration response of a steel plate under different mounting conditions to identify natural frequencies, mode shapes, and changes in structural stiffness.

---

## 🔧 Hardware Overview

- **STM32 Nucleo-H753ZI**  
  ARM Cortex-M7 MCU used for sensor interfacing, time-synchronous data sampling, and communication.

- **EVAL-ADXL355Z Accelerometers (SPI)**  
  Low-noise MEMS accelerometers providing 3-axis high-resolution vibration data.

- **Sensirion SHT40 (I²C)**  
  Measures ambient temperature and humidity for environmental compensation of vibration data.

- **Steel Test Plate**  
  Dimensions approx. 30 × 3 mm and 0.5–1.0 m long.  
  Tested with several boundary conditions (e.g., clamped, simply supported).

---

## 🎯 Project Goals

- Acquire synchronized vibration and environmental data.
- Extract natural frequencies and evaluate modal behavior.
- Study how boundary conditions affect modal properties.
- Explore stiffness changes based on frequency shifts.
- Build a foundation for low-cost SHM sensing, monitoring, and future digital twin integration.

---

## 📈 Data Processing

Collected data will be analyzed using Python or MATLAB to perform:

- FFT and spectral analysis  
- PSD (Welch)  
- Peak picking  
- Basic modal identification  
- Environmental compensation (temperature/humidity effects)

---

