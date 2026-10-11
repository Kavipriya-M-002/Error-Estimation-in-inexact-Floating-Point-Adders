# Error Estimation in Inexact Floating Point Adders

## 🔍 Overview

This project focuses on implementing and evaluating an inexact IEEE-754 single-precision floating-point adder using Verilog HDL. The study analyzes numerical deviations between exact and approximate floating-point addition results using statistical error-estimation metrics. The design explores approximate arithmetic techniques, including inexact exponent subtraction, mantissa addition, and normalization, for error-tolerant, low-power computing applications.

## 🛠️ Tools & Technology Stack

| Category | Tools / Technology |
|---|---|
| Hardware Description | Verilog HDL |
| Design Simulation | Xilinx Vivado |
| Target Platform | Xilinx Artix-7 FPGA |
| Arithmetic Standard | IEEE-754 Single Precision (Binary32) |
| Design Focus | Inexact Arithmetic, Floating-Point Adder, Error Estimation |
| Verification | RTL Functional Simulation, Waveform Analysis |

## ⚙️ Methodology

- **RTL Design:** Implemented the inexact floating-point adder using Verilog HDL.
- **Arithmetic Operations:** Applied approximate exponent subtraction and mantissa addition.
- **Result Comparison:** Compared exact and inexact floating-point outputs.
- **Error Calculation:** Calculated absolute and relative errors.
- **Statistical Analysis:** Evaluated mean, maximum, and RMS error.
- **Simulation:** Verified the design behavior through Xilinx Vivado simulation and waveform analysis.

## 📊 Key Results

The project evaluates the numerical accuracy of the inexact floating-point adder using the following error metrics:

| Metric | Purpose |
|---|---|
| Absolute Error | Measures the difference between exact and approximate results. |
| Relative Error | Measures the error relative to the magnitude of the exact result. |
| Mean Absolute Error | Evaluates the average absolute deviation across test samples. |
| Maximum Absolute Error | Identifies the largest absolute deviation observed. |
| RMS Error | Measures the overall magnitude of numerical deviations. |

The simulation framework compares exact and inexact addition results and provides statistical measures to characterize the accuracy of the approximate arithmetic design. Numerical error values should be added from verified simulation outputs.

## 📈 Error Analysis

- **Exact Floating-Point Adder:** Provides the reference result for evaluating numerical deviations.
- **Inexact Floating-Point Adder:** Uses approximate arithmetic blocks to generate an approximate floating-point result.
- **Absolute and Relative Error:** Quantify the difference between the reference and approximate outputs.
- **Statistical Evaluation:** Mean, maximum, and RMS error metrics characterize the observed numerical deviations across test samples.
- **Accuracy Assessment:** The project examines relative error against the single-precision unit round-off criterion described in the study.

## 🎯 Key Takeaway

This project demonstrates the implementation of an inexact floating-point arithmetic architecture and a statistical error-estimation framework using Verilog HDL and Vivado. It explores the trade-off between numerical accuracy and hardware efficiency in error-tolerant computing applications.

## 💡 Skills Demonstrated

- Verilog RTL Design
- IEEE-754 Single-Precision Floating-Point Arithmetic
- Digital Design and Functional Simulation
- Approximate Computing
- Floating-Point Error Analysis
- Statistical Error Estimation
- RTL Schematic and Waveform Analysis
- Xilinx Vivado and FPGA Design Fundamentals
