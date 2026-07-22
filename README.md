<div align="center">

# Ethan

**Digital Hardware Engineer** &nbsp;·&nbsp; RTL Design / Verification / FPGA System Integration

<h3>Bridging Materials Science and Digital Logic Design</h3>

<sub>`SystemVerilog` &nbsp;·&nbsp; `UVM` &nbsp;·&nbsp; `RISC-V` &nbsp;·&nbsp; `FPGA` &nbsp;·&nbsp; `C`</sub>

<br>

<a href="mailto:khb030508111@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/ethan000106"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>

<!-- 링크가 준비되면 아래 두 줄의 주석을 풀고 URL을 교체하세요.
     (링크가 비어 있는 배지는 노출하지 않는 편이 좋습니다)
<a href="https://www.linkedin.com/in/YOUR_ID"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://YOUR_RESUME_LINK"><img src="https://img.shields.io/badge/Resume-4B5563?style=flat-square&logo=readthedocs&logoColor=white" alt="Resume"></a>
-->

</div>

---

## About

- **신소재공학(Advanced Materials Engineering)** 전공으로 반도체 물성과 물리적 동작 메커니즘을 이해하고 있습니다.
- **1.5년간의 학부 연구실 경험**(접착 소재 연구)을 통해 데이터 분석력과 집요한 논리적 문제 해결 역량을 길렀습니다.
- 디지털 시스템을 **RTL 설계 → 검증 → 보드 구동**까지 직접 만들어 보는 것을 좋아합니다.
- **FSM 설계, 프로토콜 인터페이스, 타이밍 이슈 디버깅**에 관심이 많습니다.
- "동작한다"에서 멈추지 않고, **왜 동작하는지 파형으로 반드시 확인**하는 편입니다.

---

## What I Can Do

| 영역 | 내용 |
|:--|:--|
| **RTL Design** | FSM 기반 제어 로직, 파이프라인 데이터패스, 클럭 도메인 분리 설계 |
| **Verification** | UVM 환경 구축(Driver / Monitor / Scoreboard), SVA 기반 프로토콜 체크, 커버리지 기반 검증 |
| **Interface** | UART / SPI / I2C(SCCB) / AXI4-Lite 마스터·슬레이브 직접 구현 |
| **Bring-up & Debug** | 합성·타이밍 리포트 해석, ILA 캡처, CDC / 메타스테이빌리티 대응 |
| **System Integration** | FPGA + 호스트(Python / Jetson) 연동, 카메라 파이프라인 구성 |

---

## Tech Stack

| Category | Tools |
|:--|:--|
| **HDL & Verification** | ![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1F2937?style=flat-square) ![Verilog](https://img.shields.io/badge/Verilog-1F2937?style=flat-square) ![UVM](https://img.shields.io/badge/UVM-374151?style=flat-square) ![SVA](https://img.shields.io/badge/SVA-374151?style=flat-square) |
| **Language** | ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **EDA & Tools** | ![Vivado](https://img.shields.io/badge/Vivado-0B6C8C?style=flat-square) ![Vitis](https://img.shields.io/badge/Vitis-0B6C8C?style=flat-square) ![Synopsys VCS](https://img.shields.io/badge/Synopsys%20VCS-1F6F5C?style=flat-square) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **Interface** | ![UART](https://img.shields.io/badge/UART-4B5563?style=flat-square) ![SPI](https://img.shields.io/badge/SPI-4B5563?style=flat-square) ![I2C](https://img.shields.io/badge/I2C-4B5563?style=flat-square) ![AXI4-Lite](https://img.shields.io/badge/AXI4--Lite-4B5563?style=flat-square) ![SCCB](https://img.shields.io/badge/SCCB-4B5563?style=flat-square) |
| **Board / Device** | ![Basys3](https://img.shields.io/badge/Basys3-A855F7?style=flat-square) ![Artix-7](https://img.shields.io/badge/Artix--7-A855F7?style=flat-square) ![Jetson Nano](https://img.shields.io/badge/Jetson%20Nano-76B900?style=flat-square&logo=nvidia&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) |

<!-- 실제로 다뤄본 툴(Verdi, Design Compiler, PrimeTime 등)이 더 있다면 EDA 행에 추가하고,
     경험이 얕은 툴은 빼는 편이 면접에서 안전합니다. -->

---

## Projects

| Project | Summary | Stack | Result |
|:--|:--|:--|:--|
| **FPGA Whack-a-Mole Game** | 2-board FPGA 시스템. UART 패킷 통신 기반 게임 로직 + OV7670 카메라 HSV 색 검출 타격 판정 | `SystemVerilog` `UART` `VGA` `OpenCV` | *TODO: 동작 클럭 / LUT·FF·BRAM 사용률* |
| **OV7670 Camera Pipeline** | SCCB 초기화 ROM 설계, 프레임 버퍼 → VGA 출력, HSV 색상 검출 모듈 | `SystemVerilog` `SCCB/I2C` `VGA` | *TODO: 해상도 / 프레임레이트* |
| [**RISC-V RV32I Core**](https://github.com/ethan000106/rv32i_multi) | 5-stage pipeline CPU, hazard detection & forwarding unit 구현 | `SystemVerilog` `RV32I` | *TODO: 최대 동작 주파수 / CPI* |
| **UVM Verification Env** | Generator–Driver–Monitor–Scoreboard 구조 기반 FSM / 프로토콜 검증 환경 구축 | `UVM` `SystemVerilog` | *TODO: 코드 / 기능 커버리지 %* |
| **Ultrasonic Distance Module** | HC-SR04 인터페이스 FSM, Q16 고정소수점 거리 연산 | `SystemVerilog` `Basys3` | *TODO: 측정 오차 범위* |

<!-- TODO
  1) 각 프로젝트 이름에 저장소 링크를 걸어주세요.
     예) | [**FPGA Whack-a-Mole**](https://github.com/ethan000106/REPO_NAME) | ... |
  2) Result 열은 면접관이 가장 먼저 보는 칸입니다. 반드시 실측값으로 채우세요.
     - 동작 주파수 / WNS  : Vivado > Report Timing Summary
     - LUT / FF / BRAM    : Vivado > Report Utilization
     - 커버리지            : 시뮬레이터 coverage report
-->

---

<details>
<summary><b>🔍 Selected Debug Cases</b> &nbsp;<sub>— 직접 잡은 버그와 원인</sub></summary>

<br>

| Symptom | Root Cause | Fix |
|:--|:--|:--|
| 특정 조건에서 FSM이 멈춤 | `default` 미정의로 illegal state 진입 후 복귀 불가 | 전체 상태 인코딩 + `default` 복귀 경로 추가 |
| 이벤트가 여러 번 트리거됨 | level 신호를 edge 조건처럼 사용 | 1-cycle pulse 생성 로직으로 변경 |
| 통신 중 패킷이 간헐적으로 유실 | checksum 불일치 시 재동기화 미구현 | RX FSM에 resync 상태 추가 |
| 버튼 입력이 튐 | 비동기 입력 + 채터링 | 2-FF 동기화기 + 디바운스 카운터 |

<sub>실제로 겪은 케이스만 남기고, 파형 캡처 이미지를 함께 올리면 설득력이 크게 올라갑니다.</sub>

</details>

<details>
<summary><b>⚙️ Design & Verification Flow</b></summary>

<br>

```mermaid
flowchart LR
    A["Spec / Architecture"] --> B["RTL Design"]
    B --> C["Simulation<br/>Testbench · UVM"]
    C --> D["Coverage<br/>Code · Functional"]
    D --> E["Synthesis<br/>Timing Closure"]
    E --> F["Implementation<br/>Place & Route"]
    F --> G["On-Board Bring-up<br/>ILA Debug"]
    G -->|"Fix & Iterate"| B
```

</details>

---

## Currently Learning

![AXI4 Full](https://img.shields.io/badge/AXI4%20Full-4B5563?style=flat-square)
![CDC](https://img.shields.io/badge/CDC%20Handling-4B5563?style=flat-square)
![DFT](https://img.shields.io/badge/DFT%20·%20MBIST%2FBIRA%2FBISR-4B5563?style=flat-square)
![STA](https://img.shields.io/badge/Static%20Timing%20Analysis-4B5563?style=flat-square)

---

## Education

<!-- TODO: 학교 / 전공 / 수료 과정 / 자격증을 채워주세요 -->
- **OOO University** — 신소재공학과 (20XX ~ 20XX)
- **OOO 과정 수료** — RTL 설계 및 검증 / On-Device AI (20XX)

---

## GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=ethan000106&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=tokyonight" alt="GitHub Stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ethan000106&layout=compact&hide_border=true&langs_count=6&theme=tokyonight" alt="Top Languages" />

</div>

---

<div align="center">
<sub>Built with SystemVerilog, coffee, and a lot of waveform staring.</sub>
</div>
