# Breast Cancer Detection Using Microstrip Patch Antenna (CST + C Postprocessing)

This project demonstrates a non-invasive method for breast cancer detection using a microstrip patch antenna designed and simulated in CST Studio Suite 2024. The antenna’s response is analyzed through S-parameters (S11 and S21), both with and without a tumor present. A C program processes the exported results to detect anomalies based on frequency shift and amplitude variations.

## Features

- CST-based patch antenna simulation for biomedical sensing
- S11 and S21 data compared between tumor and non-tumor cases
- C program automatically detects variations indicating a tumor
- Threshold-based detection using frequency shift, S11 dip, and S21 change

## Tools Used

- CST Studio Suite 2024 – Antenna design and simulation  
- C Language (GCC on macOS) – Post-processing and detection logic  
- Visual Studio Code – Code development and execution  
- MATLAB – Graph plotting and visual analysis of S-parameter data

## How It Works

1. Simulate antenna behavior in CST with and without tumor presence.
2. Export S-parameter results into a .txt file.
3. Use the C program to read and analyze data.
4. Detection is based on observed differences in resonant frequency and transmission.

