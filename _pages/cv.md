---
layout: archive
title: "About Me"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Research Interests

* Confidential Computing (e.g., Intel SGX, and AMD SEV)
* Secure Machine Learning, Big-data Analysis
* Fuzz Testing

## Education

* Ph.D., Electrical and Computer Engineering, Seoul National University, Mar. 2017 ~
  * Advisor: [Byoungyoung Lee](https://lifeasageek.github.io/)
  * Advisor before moving into Compsec lab: [Sunghyun Choi](https://kr.linkedin.com/in/sunghyun-choi-b20268)

* B.S., Electrical Engineering, Pohang University of Science and Technology, Mar. 2013 ~ Feb. 2017.

## Projects

* **[2023.02 - ]** Designing a secure big-data analysis platform to protect data
  * Implemented the framework using [Intel SGX](https://github.com/intel/linux-sgx), and [Spark](https://github.com/apache/spark).

* **[2023.02 - 2023.05]** Fuzzing gramine libos for hardening the TCB inside SGX [[code](https://github.com/JaewonHur/graminer)]
  * Implemented the fuzzer using [syzkaller](https://github.com/google/syzkaller).
    * Published a paper to SysTEX 2023 [[paper](https://jaewonhur.github.io/files/jwhur-graminer.pdf)][[slide](https://jaewonhur.github.io/files/jwhur-graminer-slides.pdf)].

* **[2022.05 - ]** Automated stock trading application for the people who always lose their money
  * Published an Android App, [MumeParrot](https://play.google.com/store/apps/details?id=com.mumemume.mumeparrot).

* **[2022.03 - ]** Designing an efficient, and scalable confidential serverless computing framework
  * Implemented the framework using [Intel SGX](https://github.com/intel/linux-sgx), [Gramine](https://github.com/gramineproject/gramine), and [Openwhisk](https://github.com/apache/openwhisk).

* **[2021.11 - ]** Designing a secure machine-learning platform to protect training data
  * Implemented the framework using [AMD SEV](https://github.com/AMDESE/AMDSEV), [PyTorch](https://github.com/pytorch/pytorch), and [grpc](https://github.com/grpc).

* **[2021.05 - 2022.10]** Hardware fuzzing to find transient execution vulnerabilities in RISC-V CPUs [[code](https://github.com/compsec-snu/specdoctor)]
  * Implemented the fuzzer using [Verilator](https://github.com/verilator/verilator), [Chipyard](https://github.com/ucb-bar/chipyard), [Chisel](https://github.com/chipsalliance/chisel3), and [Firrtl](https://github.com/chipsalliance/firrtl).
  * Found 2 new transient execution vulnerabilities in [RISC-V Nutshell](https://github.com/OSCPU/NutShell), and [RISC-V Boom](https://github.com/riscv-boom/riscv-boom).
  * Published a paper to ACM CCS 2022 [[paper](https://jaewonhur.github.io/files/jwhur-specdoctor.pdf)][[slide](https://jaewonhur.github.io/files/jwhur-specdoctor-slides.pdf)].

* **[2021.03 - 2022.02]** Firmware fuzzing to find bugs in Samsung secure elements
  * Implement the SoC emulator using [QEMU](https://github.com/qemu/qemu).
  
* **[2019.09 - 2021.05]** Hardware fuzzing to find functional bugs in RISC-V CPUs [[code](https://github.com/compsec-snu/difuzz-rtl)]
  * Implemented the fuzzer using [Verilator](https://github.com/verilator/verilator), [Spike](https://github.com/riscv-software-src/riscv-isa-sim), [Firrtl](https://github.com/chipsalliance/firrtl), and [Cocotb](https://github.com/cocotb/cocotb).
  * Found 16 new bugs, including 6 CVEs in RISC-V CPUs.
  * Published a paper to IEEE S&P 2021 [[paper](https://jaeownhur.github.io/files/jwhur-difuzzrtl.pdf)][[slide](https://jaewonhur.github.io/files/jwhur-difuzzrtl-slides.pdf)].

