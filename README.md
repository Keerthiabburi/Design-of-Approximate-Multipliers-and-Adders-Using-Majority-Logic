# Design of Approximate Multipliers and Adders Using Majority Logic

This project explores the design and implementation of low-power, approximate arithmetic units using majority logic, targeting energy-efficient hardware for edge and embedded systems. By compromising on exact computation, these designs achieve reduced area and power consumption while maintaining acceptable accuracy.

## 🧠 Overview

Traditional digital multipliers and adders are accurate but resource-intensive. This project focuses on majority logic-based arithmetic units that reduce power, delay, and hardware complexity, making them ideal for low-power and real-time applications.

## 🔧 Features

- Approximate full adder and compressor design using majority logic.
- Four adder variants (`MLAFA11`, `MLAFA22`, `MLAFA12`, `MLAFA21`) and compressor configurations tested.
- Selected best-performing adder (`MLAFA21`) and compressor (`MLAC11`) based on MAE and NMED.
- Designed an approximate multiplier integrating selected components.
- Simulated and verified using Xilinx Vivado.
- Implemented on Basys-3 FPGA for real-time testing.

## 🛠 Tools & Technologies

- **Verilog HDL**
- **Xilinx Vivado**
- **Basys-3 FPGA Board**
- Majority Logic Arithmetic Design

## 📊 Error Metrics Used

- **MAE** (Mean Absolute Error)
- **NMED** (Normalized Mean Error Distance)

## 📈 Results

- Achieved ~80–90% accuracy in computation.
- Reduced circuit complexity and power usage.
- Successful hardware synthesis and timing analysis.
- FPGA implementation validated real-world feasibility.

## 📚 References

1. W. Liu et al., *"Design and Analysis of Majority Logic-Based Approximate Adders and Multipliers"*, IEEE TETC, 2021.
2. M. Pokharia et al., *"Power-Efficient Approximate Multipliers Leveraging Hybrid CMOS-Memristor Paradigm"*, APCCAS, 2023.
3. A. Singh et al., *"Design of a 4–2 Compressor-based Approach for Efficient Approximate Multiplier Design"*, ICITEICS, 2024.

## 👥 Contributors

- A Sai Keerthi  
- Anisha Raphael  
- B A V N Hasini  
- **Mentor:** Dr. Sushant Shendre

## 📌 Future Work

- Explore advanced multiplier architectures for higher precision.
- Optimize for real-time processing in edge devices.
- Extend scalability for high-complexity digital systems.

---

Feel free to fork, clone, or contribute!

