# AI NPU System Design with Python and Verilog

[![GitHub stars](https://img.shields.io/github/stars/estlit/AI_NPU_System_Design_v1?style=social)](https://github.com/estlit/AI_NPU_System_Design_v1)

Welcome to the official source code repository for **"AI NPU System Design with Python and Verilog"**. This project provides a complete, from-scratch guide to building an AI Neural Processing Unit (NPU), covering everything from Custom ISA and Compiler design to RTL and FPGA implementation.

🏆 **#1 New Release in Amazon Compiler Design | Full-stack AI NPU Design (Python, Verilog, ISA, FPGA)** ⭐ **5.0 out of 5 stars Rating** 🎖️ **Top 15 in Microprocessor Design**

---

## 🌟 Support this Project
If this project helps your research or learning, please give it a ⭐ **Star**! Your support is a great motivation for updating more advanced NPU examples and maintaining this repository.

---

## 🚀 Learning Path & Project Structure
The examples are organized into four distinct stages based on the learning progression:

1. **Stage 00: Concept** - Fundamental architecture modeling and NPU theory.
2. **Stage 01: Single Verification** - Unit testing for individual NPU modules and ISA decoding.
3. **Stage 02: Mass Verification** - Batch processing and performance validation with 100+ MNIST samples.
4. **Stage 03: Processor Extension** - Full integration and implementation on physical FPGA hardware.

---

## 💻 System Environment
To reproduce the results exactly as described in the book, we recommend the following environment:

| Category | Item | Specification |
| :--- | :--- | :--- |
| **Operating System** | OS | Windows 11 Pro (Version 24H2) |
| **Software & Language** | Distribution | Anaconda (Python 3.13.5) |
| | Required Library | numpy, tensorflow, matplotlib |
| **EDA Tool** | Software | **Xilinx Vivado ML Edition 2024.1** (or later) |
| **Target Hardware** | FPGA Board | **Digilent Arty S7-25 (Spartan-7)** |
| | FPGA Part | **xc7s25csga324-1** |

---

## 📂 Repository Contents
* `MNIST_System_Design.zip`: Comprehensive project package including:
  * **Python: MNIST Training Script**: Full script for training with **60,000 samples**. Extracts optimized weights and biases for the NPU.
  * **Custom Compiler (Python)**: Generates custom ISA-based machine code (`program.hex`) from high-level models.
  * **RTL Source Code (Verilog)**: Core hardware implementation of CNN blocks including **Convolution (Conv), Pooling, Fully Connected (FC), and Argmax**. 
  * **Excel: Systolic_matrix**: A reference sheet for PE Array operations and matrix multiplication logic.
  * **Mass Verification Testbenches**: Automated environments to validate inference accuracy across 100+ MNIST samples.
  * **Pre-processed Data (100 Samples)**: MNIST test dataset converted into HEX format for immediate RTL simulation and hardware verification.
  * **Constraints (XDC)**: Physical pin-mapping and timing constraints for the **Digilent Arty S7-25**.

---

## 📖 About the Book
This book is a comprehensive roadmap for anyone who wants to understand the inner workings of AI hardware. By the end of this journey, you will have built a functional NPU system capable of handwritten digit recognition (MNIST), starting from a blank page.

[Available on Amazon](https://www.amazon.com/System-Design-Python-Verilog-Implementation-ebook/dp/B0GLQVJWMK/ref=sr_1_1_sspa?crid=31P3PUU4BB4YK&dib=eyJ2IjoiMSJ9.kWSm1cC5MV4e9bm7vrP5cVzlXCeX_RzrZepGkgUAQlU7T3_oI568VPauzKc-HRrrItWP0KgMMcQ4tFLTn3T9DL8YQlsdqBcwAGdqGQEE_P4qq41c-SJyOD7vZ-KjklhvUBuW9uRnBNE20SIBf-tTSNPhvSoIbpU-eO-Ua8YLJ5jkI74iXck8mD7Jq6Lp-KVZK_Vc8Xk2dqvQjb0DUjJerlUZENnr79CXlPb3A0bdFao.gqGt-kVdqwqRp310WNOPwHEBZhglXzrXogwbjjMsTvQ&dib_tag=se&keywords=ai+npu+system+design&qid=1770518537&sprefix=%2Caps%2C292&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)
