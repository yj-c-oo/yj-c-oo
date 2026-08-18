# 조유정 (Cho Yoo Jung)

**RTL Design & Design Verification**

설계한 회로가 의도대로 동작하는지 파형 단위로 끝까지 추적하는 과정에 가장 몰입합니다.
RTL 설계와 UVM 검증을 중심에 두고, 그 앞뒤 단계(합성·P&R, 아날로그)까지 경험의 폭을 넓혀왔습니다.

📫 yoojung4011@gmail.com

---

## Experience

| 기간 | 내용 |
|---|---|
| 2026.01 – 2026.08 | **대한상공회의소 서울기술교육센터** — OnDevice AI 시스템반도체 설계 (980H)<br>RTL 설계 · FPGA Implementation · UVM 기반 검증 · ARM Cortex-M 기반 STM32 임베디드 펌웨어 개발 |
| 2025.06 – 2025.08 | **한국반도체아카데미 (KSA)** — 파운드리향 반도체 Design 전문가 양성과정 (300H)<br>Synthesis, LEC, STA, SCAN/ATPG (PI) · Auto P&R (PD) · DRC, LVS (PV) · **원장상** (팀 1위 수료) |
| 2022.03 – 2026.02 | **광운대학교** 전자공학과 / 인공지능반도체 연계전공 졸업 |
| 2022.03 – 2026.02 | **전자연구회** (교내 중앙학술동아리) — MCU 기반 임베디드 작품 제작, 1년간 임원으로 운영 참여 |
| 2022.03 – 2026.02 | **TIME** (교내 중앙학술동아리) — 영어 시사 토론 동아리 |
| 2022.07 – 2022.08 | **동대문구 대학생 멘토링** — 고등학교 2학년 학생 대상 수학 교과목 8주간 지도 |

---

## Certifications & Language

| 항목 | 내용 | 취득 |
|---|---|---|
| **OPIc** (English) | **IH** (Intermediate High) | 2026.06 |
| **데이터분석 준전문가 (ADsP)** | 한국데이터산업진흥원 | 2025.03 |

<sub>단기 수료: IDEC 「SystemVerilog를 이용한 검증 방법론」, 「Standard Cell Based Design (RTL-to-GDSII)」, 「AI 반도체 센서용 PCB 설계」, NVIDIA DLI 딥러닝 기초</sub>

---

## Skills

**Programming Language**  ·  Verilog, SystemVerilog, C++, Python, Tcl

**Design & Verification**

| 구분 | 내용 |
|---|---|
| Design | AMBA AXI4-Lite · AMBA APB · SPI · I2C · UART · RISC-V RV32I · FSM · FIFO · CDC · MMIO |
| Verification | UVM · Constrained Random Verification · Functional Coverage · Virtual Sequence · Scoreboard |
| RTL-to-GDS | **PI** — Synthesis, LEC, STA, SCAN/ATPG<br>**PD** — Floorplan, Powerplan, Placement, CTS, Route, Chip Finish<br>**PV** — DRC, LVS |

**Tools**

| 구분 | 툴 |
|---|---|
| FPGA | Vivado, Quartus, Vitis IDE |
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
| [**FPGA 기반 실시간 영상처리 Air Drawing System**](https://github.com/yj-c-oo/FPGA_AirDrawing_Video_Processing) | 2026.07 | 카메라로 잡은 마커의 궤적을 화면에 그려주는 시스템. 색 검출부터 브러시 렌더링까지 전 과정을 FPGA에서 처리하고, 9개 RTL 모듈에 UVM 검증 환경 구축 | VGA Timing, SCCB, Frame Buffer, CDC, UART, UVM |
| [**MicroBlaze 기반 Custom AXI SoC**](https://github.com/yj-c-oo/SoC_MicroBlaze_AXI_Peripheral) | 2026.04 | AXI4-Lite 인터페이스의 SPI/I2C Peripheral IP를 직접 설계해 MicroBlaze SoC에 통합. 보드 간 통신 구현 및 UVM 검증 | AXI4-Lite, UVM, MicroBlaze, Vitis |
| [**SPI · I2C 프로토콜 설계 및 검증**](https://github.com/yj-c-oo/SPI_I2C_RTL_UVM) | 2026.03 – 2026.04 | 공식 규격 기반 Master/Slave RTL 설계, FPGA 보드 간 송수신 확인 및 UVM 검증 | SystemVerilog, UVM, URG |
| [**RISC-V Multi-Cycle CPU & APB Bus**](https://github.com/yj-c-oo/RV32I_Multi_APB_Peripheral) | 2026.03 | RV32I Multi-cycle CPU와 APB Master 설계, MMIO 방식 Peripheral 구성 | RISC-V, AMBA APB, MMIO |
| [**RISC-V Single-Cycle CPU**](https://github.com/yj-c-oo/RISCV_RV32I_Single) | 2026.02 – 2026.03 | RV32I 37개 명령어 전체를 지원하는 CPU 설계, C 코드를 컴파일해 동작 검증 | RISC-V, SystemVerilog, gcc |
| [**Watch/Stopwatch & 센서 제어 시스템**](https://github.com/yj-c-oo/FPGA_Stopwatch_Watch_Sensors_Control_System) | 2026.01 – 2026.02 | FPGA 보드를 시계·스톱워치로 동작시키고 PC에서도 제어하는 시스템. UART·FIFO 통신 경로와 센서 제어 모듈 설계 | Verilog, UART, FIFO, FSM |
| **FPGA 기반 Adaptive Cruise Control System** | 2025.03 – 2025.06 | 앞차와의 거리를 유지하며 따라가는 RC카를 FPGA로 구현. 센서 인터페이스·PWM·PID 제어 모듈과 HPS-FPGA 간 AXI Bridge로 구성 | Verilog, AXI Bridge, PID, I2C, Quartus |
| **AES-256 GCM 암호화 가속기 설계 및 검증** | 2026.07 – 2026.08 | *(작성 예정)* | — |

### ASIC Implementation — RTL to GDS (PI · PD)

| 프로젝트 | 기간 | 내용 | 주요 기술 |
|---|---|---|---|
| **RTL to GDS: 715MHz Block Counter on 100×100 Chip** <br>*(한국반도체아카데미 원장상)* | 2025.08 | Samsung 28nm LP 공정에서 RTL 설계부터 GDS까지 PI·PD 전 과정 수행. Clock period 5ns→1.4ns, Chip size 120×120→100×100um²로 개선해 714.28MHz 달성 | Design Compiler, Formality, PrimeTime, TestMAX, Innovus |

### Analog Circuit Design

| 프로젝트 | 기간 | 내용 | 주요 기술 |
|---|---|---|---|
| **20MHz 8bit Asynchronous SAR ADC** | 2025.09 – 2025.11 | 아날로그 전압을 8bit 디지털 코드로 변환하는 비동기 SAR ADC. gpdk045 공정에서 트랜지스터 단위로 전체 회로를 설계·시뮬레이션해 20MHz 동작, FoM 0.0117 달성 | Cadence Virtuoso, gpdk045 |

### Deep Learning & Embedded

| 프로젝트 | 기간 | 내용 | 주요 기술 |
|---|---|---|---|
| [**Vision AI를 활용한 Auto Cashier System**](https://github.com/yj-c-oo/Vision_AI_Auto_Cashier) | 2026.06 | 바코드 없이 카메라만으로 상품을 인식해 자동 결제하는 무인 키오스크. 커스텀 데이터셋 학습과 TensorRT 최적화로 Jetson에서 실시간 추론, mAP50 0.990 달성 | YOLOv11m, TensorRT, OpenCV, Jetson Orin Nano |
| **졸음운전 방지 자율주행 RC카** | 2024.09 – 2024.12 | 차선을 인식해 스스로 주행하고 운전자 졸음을 감지해 경보하는 RC카. 직접 수집한 주행 이미지 8,000장으로 학습 (11팀 중 2위) | CNN, TensorFlow, OpenCV, Raspberry Pi |
