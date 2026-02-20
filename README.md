# AI NPU System Design with Python and Verilog

[![GitHub stars](https://img.shields.io/github/stars/estlit/AI_NPU_System_Design_v1?style=social)](https://github.com/estlit/AI_NPU_System_Design_v1)
<div align="center">
  <img src="https://img.shields.io/badge/Amazon-1%20New%20Release-FF9900?style=for-the-badge&logo=amazon&logoColor=white" />
  <img src="https://img.shields.io/badge/Microprocessor%20Design-%231-gold?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Compiler%20Design-%231-gold?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Best%20Seller-Rank%20%236-007EB9?style=for-the-badge" />
</div>
Welcome to the official source code repository for **AI NPU System Design with Python and Verilog**. This project provides a complete, from-scratch guide to building an AI Neural Processing Unit (NPU), covering everything from Custom ISA and Compiler design to RTL and FPGA implementation.


🏆 **Amazon Best Seller #3 in Compiler Design | #4 in Microprocessor Design | #5 in Microprocessors & System Design** ⭐ **5.0 out of 5 stars Rating** 
---

### 🎊 **Milestone: 500+ Views & Free Sample Release!**
To celebrate reaching **500+ views** and our **Amazon Top 4** ranking, we are releasing a **45-page Premium Sample** for the community!

📖 **[Download Free Sample PDF (CH1, CH2 & Appendix A)](./AI%20NPU%20System%20sample_Roger_Kim.pdf)**
* **Chapter 1 & 2:** Introduction to NPU Architecture & Design Philosophy.
* **Appendix A:** Full Environment Setup Guide (Windows 11, Python 3.13, Vivado 2024.1).
* *Learn why AI semiconductors are proven by bits, not concepts.*

---

## 🚀 Coming Soon: Volume 2
**"Advanced AI NPU System Design with Python and Verilog"**

* **Target:** CIFAR-10 Color Image Recognition
* **Key Strategy:** 4-NPU, 4-Cycle Resource Reuse & Ensemble Decision Unit (EDU)
* **Status:** Development Completed. Amazon Publication Coming Soon!

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
