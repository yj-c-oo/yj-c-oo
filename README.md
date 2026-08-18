# 조유정 (Cho Yoo Jung)

**RTL Design & Design Verification**

설계한 회로가 의도대로 동작하는지 파형 단위로 끝까지 추적하는 과정에 가장 몰입합니다.
RTL 설계와 UVM 검증을 중심에 두고, 그 앞뒤 단계(합성·P&R, 아날로그)까지 경험의 폭을 넓혀왔습니다.

📫 yoojung4011@gmail.com

---

## Experience

| 기간 | 내용 |
|---|---|
| 2026.01 – 2026.08 | **대한상공회의소 서울기술교육센터** — OnDevice AI 시스템반도체 설계 (980H)<br>RTL 설계 · FPGA Implementation · UVM 기반 검증 · AMBA AXI4 Peripheral IP 설계 |
| 2025.06 – 2025.08 | **한국반도체아카데미 (KSA)** — 파운드리향 반도체 Design 전문가 양성과정 (300H)<br>Synthesis, LEC, STA, SCAN/ATPG (PI) · Auto P&R (PD) · DRC, LVS (PV) · **원장상** (팀 1위 수료) |
| 2022.03 – 2026.02 | **광운대학교** 전자공학과 / 인공지능반도체 연계전공 졸업 |
| 2022.03 – 2026.02 | **전자연구회** (교내 중앙학술동아리) — MCU 기반 임베디드 작품 제작, 1년간 임원으로 운영 참여 |

<sub>그 외: IDEC 「SystemVerilog 검증 방법론」·「Standard Cell Based Design (RTL-to-GDSII)」 수료, ADsP, OPIc IH</sub>

---

## Skills

**Programming Language**  ·  Verilog, SystemVerilog, C++, Python, Tcl, MATLAB

**Design & Verification**

| 구분 | 내용 |
|---|---|
| Design | AMBA AXI4-Lite, APB · SPI, I2C, UART · RISC-V RV32I · FSM, FIFO, CDC, MMIO |
| Verification | UVM · Constrained Random Verification · Functional Coverage · Virtual Sequence, Scoreboard |
| RTL-to-GDS | **PI** — Synthesis, LEC, STA, SCAN/ATPG<br>**PD** — Floorplan, Powerplan, Placement, CTS, Route, Chip Finish<br>**PV** — DRC, LVS |

**Tools**

| 구분 | 툴 |
|---|---|
| FPGA | Vivado, Quartus, Vitis IDE · Basys3(Artix-7), DE10-Standard |
| RTL Simulation | VCS (Verdi), Questa (Visualizer), Xcelium (SimVision) |
| Front-end (PI) | Design Compiler, Formality, PrimeTime, TestMAX |
| Back-end (PD · PV) | Innovus, ICC2 · Calibre |
| Analog Circuit | Virtuoso, PSpice, LTSpice |
| Modeling / CAD | AutoCAD, OrCAD, Fusion360 |

---

## Projects

### RTL Design & Verification

| 프로젝트 | 기간 | 내용 | 주요 기술 |
|---|---|---|---|
| [**FPGA 실시간 영상처리 Air Drawing**](https://github.com/yj-c-oo/FPGA_AirDrawing_Video_Processing) | 2026.07 | 초록 마커 검출부터 브러시 렌더링까지 전 과정을 FPGA RTL로 구현. UART RX 경로·펜 상태 제어 RTL과 PC 오버레이 UI 담당, 9개 모듈 UVM 검증 커버리지 100% | VGA Timing, SCCB, Frame Buffer, CDC, UART, UVM |
| [**MicroBlaze 기반 Custom AXI SoC**](https://github.com/yj-c-oo/SoC_MicroBlaze_AXI_Peripheral) | 2026.04 | AXI4-Lite 인터페이스의 SPI/I2C Peripheral IP를 직접 설계해 MicroBlaze SoC에 통합, 보드 간 통신 구현 및 UVM 검증 (기능 커버리지 100%) | AXI4-Lite, UVM, MicroBlaze, Vitis |
| [**SPI · I2C 프로토콜 설계 및 검증**](https://github.com/yj-c-oo/SPI_I2C_RTL_UVM) | 2026.03 – 2026.04 | 공식 규격 기반 Master/Slave RTL 설계, FPGA 보드 간 송수신 확인, UVM 검증 (8,020 transaction PASS, Coverage 100%) | SystemVerilog, UVM, URG |
| [**RISC-V Multi-Cycle CPU & APB Bus**](https://github.com/yj-c-oo/RV32I_Multi_APB_Peripheral) | 2026.03 | RV32I Multi-cycle CPU와 APB Master 설계, MMIO 방식 Peripheral(RAM·GPIO·UART·7-seg) 구성 | RISC-V, AMBA APB, MMIO |
| [**RISC-V Single-Cycle CPU**](https://github.com/yj-c-oo/RISCV_RV32I_Single) | 2026.02 – 2026.03 | RV32I 37개 명령어 전체 구현, C 코드를 컴파일해 ROM 시뮬레이션으로 동작 검증 | RISC-V, SystemVerilog, gcc |
| [**Watch/Stopwatch & 센서 제어 시스템**](https://github.com/yj-c-oo/FPGA_Stopwatch_Watch_Sensors_Control_System) | 2026.01 – 2026.02 | UART·FIFO 기반 PC 연동 Watch/Stopwatch, 초음파·온습도 센서 제어 모듈 설계 | Verilog, UART, FIFO, FSM |
| **암호화 가속기** | *(작성 예정)* | *(작성 예정)* | — |

### ASIC Implementation — RTL to GDS (PI · PD)

| 프로젝트 | 기간 | 내용 | 주요 기술 |
|---|---|---|---|
| **RTL to GDS: 715MHz Block Counter on 100×100 Chip** <br>*(한국반도체아카데미 원장상)* | 2025.08 | Samsung 28nm LP 공정에서 RTL 설계·검증부터 GDS까지 전 과정 단독 수행.<br>**PI** — Synthesis, LEC, SCAN/ATPG, Pre-STA, Pre-Sim<br>**PD** — Floorplan, Powerplan, Placement, CTS, Route, Chip Finish<br>Clock period 5ns→1.4ns 개선으로 714.28MHz 달성, Chip size 120×120→100×100um² 축소 (Core Utilization 79.02%) | Design Compiler, Formality, PrimeTime, TestMAX, Innovus, VCS/Verdi |

### Analog Circuit Design

| 프로젝트 | 기간 | 내용 | 주요 기술 |
|---|---|---|---|
| **20MHz 8bit Asynchronous SAR ADC** | 2025.09 – 2025.11 | StrongArm Latch Comparator 및 5-TR Buffer 설계, 전체 회로 시뮬레이션. FoM 0.0117 달성 | Cadence Virtuoso, gpdk045 |

### Embedded & Vision AI

| 프로젝트 | 기간 | 내용 | 주요 기술 |
|---|---|---|---|
| **Vision AI 기반 Auto Cashier System** | 2026.06 | YOLOv11m + TensorRT로 바코드 없는 실시간 상품 인식 무인 키오스크 구현 (mAP 0.988) | Jetson Orin Nano, YOLO, OpenCV |
| **FPGA 기반 Adaptive Cruise Control System** | 2025.03 – 2025.06 | ToF 센서·로터리 엔코더 기반 계층형 PID 제어로 차간거리를 유지하는 RC카 설계. HPS-FPGA Lightweight AXI Bridge 구성 | Verilog, Quartus, PID, I2C |
| **졸음운전 방지 자율주행 RC카** | 2024.09 – 2024.12 | 직접 수집한 8,000장 데이터로 PilotNet 기반 차선 주행 학습, 얼굴 인식 졸음 감지 경보 구현 (11팀 중 2위) | CNN, TensorFlow, Raspberry Pi |

---

## Currently

- UVM 기반 검증 환경 심화 (Register Model, Assertion)
- AMBA AXI4 Full 프로토콜 및 SoC 구조 학습
