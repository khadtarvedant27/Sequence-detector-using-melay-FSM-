# Mealy FSM Sequence Detector (Verilog)

![Language](https://img.shields.io/badge/Language-Verilog_HDL-blue)
![Tool](https://img.shields.io/badge/EDA_Tool-Cadence_Incisive%2FNcVerilog-orange)
![Type](https://img.shields.io/badge/FSM_Type-Mealy_Machine-green)


## 📌 Project Overview
This repository contains the RTL implementation and Testbench for a **Sequence Detector** using a **Mealy Finite State Machine**. The design detects a specific binary pattern in a continuous stream of serial input data.

Unlike a Moore machine, the output in this Mealy design depends on both the **current state** and the **current input**, allowing the sequence to be detected one clock cycle earlier.

---

## 📊 Simulation Results

### Waveform Output
Below is a snapshot from Cadence SimVision verifying the detection logic. 
![Cadence SimVision Waveform showing sequence detection](https://github.com/user-attachments/assets/12982f82-1988-4432-9af1-d033d15fc27f)
![Cadence SimVision Waveform showing sequence detection](https://github.com/user-attachments/assets/5e3616b7-a453-4336-92e0-067db115a4bd) 
![Cadence SimVision Waveform showing sequence detection](https://github.com/user-attachments/assets/061f7ec0-dc82-43e6-8d74-447a0c55d320)
![Cadence SimVision Waveform showing sequence detection](https://github.com/user-attachments/assets/5e8e09bf-378c-473f-ba2d-be1e16118db6)

