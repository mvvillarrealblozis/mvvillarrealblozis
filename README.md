# Maximiliano Villarreal-Blozis
**MS ECE candidate at UC Davis · ASIC & Digital Design**

I'm a CS graduate (USF, Cum Laude) pursuing an MS in ECE at UC Davis, specializing in **digital design and computer architecture**. I'm building a hardware design portfolio targeting ASIC/RTL engineering roles, with a focus on pipelined microarchitecture, clock domain crossing, and synthesis.

---

## Hardware Projects

### [RISC-V Pipelined Processor](https://github.com/mvvillarrealblozis/riscv-processor-pipelined) | Verilog, RTL Design | Feb 2026 – Apr 2026
- Designed and verified a 5-stage RV32I pipelined processor with full forwarding, load-use hazard detection, and branch flush control
- EX/MEM and MEM/WB bypass paths resolve RAW dependencies while minimizing pipeline stalls
- Synthesized to Sky130 standard cells via Yosys; analyzed timing bottlenecks in decode and forwarding logic
- Self-checking testbenches covering arithmetic, memory, branch, jump, and hazard corner cases

### Dual-Clock Asynchronous FIFO | SystemVerilog, RTL Design | In Progress
- Parameterizable dual-clock FIFO using Gray code pointer synchronization across independent clock domains
- Two-flop synchronizer chains on read/write pointers with full/empty flag generation and metastability guarantees
- Functional verification testbench with configurable data width and depth

### Multi-Port Bus Arbiter | SystemVerilog, RTL Design | In Progress
- Parameterizable arbiter supporting round-robin and fixed-priority scheduling with configurable requestor count
- Fairness guarantees and starvation prevention; targets GPU scheduling and interconnect use cases
- Self-checking testbench verifying grant correctness, arbitration fairness, and edge cases

---

## Technical Skills

| | |
|---|---|
| **Languages** | Verilog, SystemVerilog, Python, C, Java |
| **Digital Design** | RTL design, pipeline architecture, CDC, FSM design, arbitration |
| **Verification** | Testbench development, simulation, waveform debugging |
| **Tools** | Yosys, Icarus Verilog, GTKWave, Git, Linux, Docker |

---

## Education

**University of California, Davis** MS, Electrical and Computer Engineering *(expected Dec 2027)*  
Coursework: VLSI Design, High Performance Computer Architecture, IC Design & Tapeout, Advanced Verification of Digital Systems

**University of San Francisco** BS, Computer Science, Cum Laude  
Dean's List · 4 semesters

---

## What I'm Working Toward

I'm targeting ASIC/RTL engineering roles at companies working on high-performance silicon processors, accelerators, and interconnects. My background in CS gives me strong footing in computer architecture; my portfolio projects are closing the gap toward industry-ready digital design skills.

Open to internship opportunities starting **Summer/Fall 2027**.

---

📂 [GitHub](https://github.com/mvvillarrealblozis) · 💼 [LinkedIn](https://www.linkedin.com/in/maximilianovb/?skipRedirect=true) · ✉️ [mvblax35@gmail.com](mailto:mvblax35@gmail.com)
