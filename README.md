# AI NPU System Design with Python and Verilog

[![GitHub stars](https://img.shields.io/github/stars/estlit/AI_NPU_System_Design_v1?style=social)](https://github.com/estlit/AI_NPU_System_Design_v1)
<div align="center">
  <img src="https://img.shields.io/badge/Amazon-1%20New%20Release-FF9900?style=for-the-badge&logo=amazon&logoColor=white" />
  <img src="https://img.shields.io/badge/Microprocessor%20Design-%231-gold?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Compiler%20Design-%231-gold?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Best%20Seller-Rank%20%236-007EB9?style=for-the-badge" />
</div>
Welcome to the official source code repository for **AI NPU System Design with Python and Verilog**. This project provides a complete, from-scratch guide to building an AI Neural Processing Unit (NPU), covering everything from Custom ISA and Compiler design to RTL and FPGA implementation.


🏆 **Amazon Best Seller #2 in Microprocessor Design | #2 in Compiler Design | #4 in Microprocessors & System Design** ⭐ **5.0 out of 5 stars Rating** 
---

[Available on Amazon:  AI NPU System Design with Python and Verilog](https://www.amazon.com/System-Design-Python-Verilog-Implementation-ebook/dp/B0GLQVJWMK/ref=sr_1_1_sspa?crid=31P3PUU4BB4YK&dib=eyJ2IjoiMSJ9.kWSm1cC5MV4e9bm7vrP5cVzlXCeX_RzrZepGkgUAQlU7T3_oI568VPauzKc-HRrrItWP0KgMMcQ4tFLTn3T9DL8YQlsdqBcwAGdqGQEE_P4qq41c-SJyOD7vZ-KjklhvUBuW9uRnBNE20SIBf-tTSNPhvSoIbpU-eO-Ua8YLJ5jkI74iXck8mD7Jq6Lp-KVZK_Vc8Xk2dqvQjb0DUjJerlUZENnr79CXlPb3A0bdFao.gqGt-kVdqwqRp310WNOPwHEBZhglXzrXogwbjjMsTvQ&dib_tag=se&keywords=ai+npu+system+design&qid=1770518537&sprefix=%2Caps%2C292&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)

### **🎊 Milestone: 500+ Views & Free Sample Release!**
To celebrate reaching **500+ views** and our **Amazon Top 3** ranking, we are releasing a **45-page Premium Sample** for the community!

> 📖 **[Download Free Sample PDF (CH1, CH2 & Appendix A)](./AI%20NPU%20System%20sample_Roger_Kim.pdf)**
* **Chapter 1 & 2:** Introduction to NPU Architecture & Design Philosophy.
* **Appendix A:** Full Environment Setup Guide (Windows 11, Python 3.13, Vivado 2024.1).
* *Learn why AI semiconductors are proven by bits, not concepts.*
---
### **🚀 Upcoming | Volume 2: Advanced AI NPU System Design**
### **[Coming Soon] Mastering Systolic Arrays & Multi-Core Parallelism"**

Volume 2 moves beyond the fundamentals, implementing high-performance architectures in real hardware (RTL). Experience the pinnacle of NPU design, from 13x10 Systolic Arrays to Quad-Core parallel systems.

### 🎬 Witness the 'Heartbeat' of the 13x10 Systolic Array**
Observe how a Systolic Array—often discussed only in theory—actually "beats" within real hardware. This section unveils the practical design and bit-level verification of a **13x10 Systolic Array** optimized for **Fully Connected Layer (FCL)** operations.
* **Demo Video (3x3 GEMM):** The video demonstrates the core systolic principles using two **3x3 matrices** from the Excel Golden Model. This simplified scale allows you to track every bit as it pulses through the PEs.
* **Book Implementation (13x10 Array):** While the demo is 3x3 for clarity, **Volume 2** provides the full RTL implementation for a **13x10 Systolic Array**, specifically optimized to handle the heavy computational demands of **Fully Connected Layers (FCL)**.

https://github.com/user-attachments/assets/6133d343-c929-4264-b2d7-c68f2ee0b053

* **Production-Scale Design:** A real-world 13x10 Processing Element (PE) array implementation optimized for MNIST and CIFAR-10 datasets.
* **Excel-to-RTL Sync:** Witness spectacular **Bit-Accuracy** where the Excel Golden Model's "pulsing" trace matches the Vivado RTL simulation with 100% precision.
* **Wavefront Visualization:** Visual proof of the unique Systolic "Wavefront" where data flows seamlessly between neighboring PEs in a synchronized pulse.

> **"Beyond MNIST: Conquering CIFAR-10 with Multi-Core Parallelism"**

### **[Coming Soon] Preview the Spectacular Bit-Accuracy of the 4-Core NPU System**


https://github.com/user-attachments/assets/e6a8d894-5b54-453e-abec-5f909283451f


* *Witness 100% Golden Match (Pass=100/Fail=0) on the CIFAR-10 dataset using our Quad-Core parallel architecture.*

* **Target:** CIFAR-10 Color Image Recognition
* **Key Strategy:** 4-NPU, 4-Cycle Resource Reuse & Ensemble Decision Unit (EDU)
* **Status:** Development Completed. Amazon Publication Coming Soon!
* **Full Packages:** RTL Source, Testbench, and Python models will be included.

---

### **✅ Proven by Bits: Volume 1 Verification Showcase**
*"AI semiconductors are proven by bits, not concepts."*

#### **1. The Digital Pulse: Bit-by-Bit Hardware Verification**

https://github.com/user-attachments/assets/b1b286b3-3dbf-42db-86bb-e8718a3217ac



*Every clock, every bit is under your control. Observe the perfect synchronization between the Python Golden Model and RTL Logic.*

#### **2. Mass Reliability: 100-Sample Automated 'Golden Match'**


https://github.com/user-attachments/assets/008cb01d-e19d-40c3-a160-810227cb5afd

*100 samples processed with zero error, proving the robustness and scalability of the NPU architecture.*

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
  * **Excel: Systolic_matrix**: A reference sheet for PE Array operations and matrix multiplication logic.(Note: The provided RTL implementation is NOT based on a systolic array architecture; this sheet is for conceptual reference only.)
  * **Mass Verification Testbenches**: Automated environments to validate inference accuracy across 100+ MNIST samples.
  * **Pre-processed Data (100 Samples)**: MNIST test dataset converted into HEX format for immediate RTL simulation and hardware verification.
  * **Constraints (XDC)**: Physical pin-mapping and timing constraints for the **Digilent Arty S7-25**.
---

## 📂 저장소 주요 구성 (Korean Version)
* `MNIST_System_Design.zip`: 다음 내용을 포함한 전체 프로젝트 패키지입니다.
  * **Python: MNIST 학습 스크립트**: 60,000개의 샘플을 활용한 전체 학습 코드입니다. NPU 하드웨어에 최적화된 가중치(Weights)와 바이어스(Biases)를 추출합니다.
  * **커스텀 컴파일러 (Python)**: 상위 수준 모델을 커스텀 ISA 기반의 기계어(`program.hex`)로 변환해주는 전용 스크립트입니다.
  * **RTL 소스 코드 (Verilog)**: 컨볼루션(Conv), 풀링(Pooling), 완전 연결 계층(FC), 아그맥스(Argmax) 등 CNN 구조의 핵심 블록을 하드웨어로 구현한 로직입니다. 
  * **Excel: Systolic_matrix**: PE 어레이(PE Array)의 동작 원리와 행렬 곱셈 로직을 시각적으로 파악할 수 있는 참조용 시트입니다. (주의: 제공된 RTL 구현은 시스톨릭 어레이 아키텍처 기반이 아니며, 이 시트는 개념적 참조용입니다.)
  * **대량 검증용 테스트벤치 (Mass Verification)**: 100개 이상의 MNIST 샘플에 대해 추론 정확도를 자동으로 검증하는 자동화 환경입니다.
  * **전처리된 데이터 (100 Samples)**: RTL 시뮬레이션 및 하드웨어 검증을 위해 즉시 사용할 수 있도록 HEX 형식으로 변환된 MNIST 테스트 데이터셋입니다.
  * **제약 조건 파일 (XDC)**: Digilent Arty S7-25 보드에 최적화된 물리적 핀 매핑 및 타이밍 제약 조건 설정 파일입니다.

---

## 📖 About the Book
This book is a comprehensive roadmap for anyone who wants to understand the inner workings of AI hardware. By the end of this journey, you will have built a functional NPU system capable of handwritten digit recognition (MNIST), starting from a blank page.

[Available on Amazon:  AI NPU System Design with Python and Verilog](https://www.amazon.com/System-Design-Python-Verilog-Implementation-ebook/dp/B0GLQVJWMK/ref=sr_1_1_sspa?crid=31P3PUU4BB4YK&dib=eyJ2IjoiMSJ9.kWSm1cC5MV4e9bm7vrP5cVzlXCeX_RzrZepGkgUAQlU7T3_oI568VPauzKc-HRrrItWP0KgMMcQ4tFLTn3T9DL8YQlsdqBcwAGdqGQEE_P4qq41c-SJyOD7vZ-KjklhvUBuW9uRnBNE20SIBf-tTSNPhvSoIbpU-eO-Ua8YLJ5jkI74iXck8mD7Jq6Lp-KVZK_Vc8Xk2dqvQjb0DUjJerlUZENnr79CXlPb3A0bdFao.gqGt-kVdqwqRp310WNOPwHEBZhglXzrXogwbjjMsTvQ&dib_tag=se&keywords=ai+npu+system+design&qid=1770518537&sprefix=%2Caps%2C292&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)
