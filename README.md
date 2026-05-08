# advanced-oscilloscope-analysis-signal-coupling-pulse-characterization-
A comprehensive laboratory study on advanced oscilloscope measurement techniques, focusing on AC/DC signal coupling, pulse timing parameters, and X-Y mode characterization of semiconductor components

This project documents a series of laboratory experiments focused on advanced signal measurement techniques using digital storage oscilloscopes (DSOs). The study covers signal integrity, frequency response, and the characterization of non-linear electronic components.

## 🚀 Objectives
* **Signal Coupling:** Analyze the high-pass filter effect of AC coupling on low-frequency signals.
* **Time Constants:** Measure and calculate pulse parameters including rise/fall times and duty cycles.
* **Component Characterization:** Use X-Y mode to plot and analyze the I-U characteristic curve of a 1N4007 Silicon Diode.

## 📊 Key Experiments & Results

### 1. AC vs. DC Coupling Impact
We observed that AC coupling introduces a lower cutoff frequency, effectively acting as a high-pass filter. 
* **Key Finding:** At frequencies below 10Hz, AC coupling significantly attenuates the signal amplitude, while DC coupling maintains signal integrity.

### 2. Pulse Timing & Symmetry
Using a square wave generator, the following parameters were captured:
* **Amplitude:** 4.64 V
* **Rise Time ($t_R$):** 211.8 μs
* **Fall Time ($t_F$):** 79.50 μs
* **Duty Cycle:** 77.8%

### 3. Diode I-U Characteristics (X-Y Mode)
By utilizing a differential probe setup, we mapped the exponential current growth of a 1N4007 diode.
* **Forward Voltage ($U_F$):** Observed starting at approximately 0.6V.
* **Calculated Current:** 1.025 mA @ 600mV | 480.01 mA @ 800mV.


<img width="1600" height="1200" alt="WhatsApp Image 2026-05-08 at 12 24 18" src="https://github.com/user-attachments/assets/a3a5785b-364e-4e27-af4e-88ed841fa7a0" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-05-08 at 12 24 23 (2)" src="https://github.com/user-attachments/assets/d74baed5-0536-4ad2-b953-525824c36a99" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-05-08 at 12 24 23 (3)" src="https://github.com/user-attachments/assets/5401ae3a-b4dc-494b-b1e6-7e92a6d89274" />

