# Maximiliano Villarreal-Blozis
**MS ECE candidate at UC Davis · ASIC & Digital Design**

I'm a CS graduate (USF, Cum Laude) pursuing an MS in ECE at UC Davis, specializing in **digital design and computer architecture**. I'm building a hardware design portfolio targeting ASIC/RTL engineering roles, with a focus on pipelined microarchitecture, clock domain crossing, bus arbitration, and logic synthesis.

---

## Hardware Projects

### [RISC-V Pipelined Processor](https://github.com/mvvillarrealblozis/riscv-processor-pipelined) | Verilog, RTL Design | Feb 2026 – May 2026
- Designed a 5-stage RV32I pipelined processor with full forwarding, load-use hazard detection, and branch flush control
- EX/MEM and MEM/WB bypass paths resolve RAW dependencies while minimizing pipeline stalls
- Synthesized to Sky130 standard cells via Yosys; analyzed timing bottlenecks in decode and forwarding logic
- Self-checking testbenches covering arithmetic, memory, branch, jump, and hazard corner cases

### [Dual-Clock Asynchronous FIFO](https://github.com/mvvillarrealblozis/dual-clock-asynchronous-fifo) | SystemVerilog, RTL Design, UVM | May 2026 – June 2026
- Parameterizable dual-clock FIFO using Gray code pointer synchronization across independent clock domains
- Two-flop synchronizer chains on read/write pointers with full/empty flag generation and metastability guarantees
- Full UVM 1.2 verification environment (driver, monitor, scoreboard, sequencer, constrained-random sequences) validated on Synopsys VCS
- Diagnosed and resolved a multi-process race condition between testbench drivers and DUT clock edges

### [Multi-Port Bus Arbiter](https://github.com/mvvillarrealblozis/multi-port-bus-arbiter) | SystemVerilog, RTL Design, UVM | June 2026 – July 2026
- Parameterizable arbiter supporting round-robin and fixed-priority scheduling with configurable max-hold timeout and aging counter-based starvation prevention
- Saturating aging counters temporarily elevate starved requestors to highest priority, preventing indefinite blocking in fixed-priority mode
- Full UVM 1.2 verification environment with constrained-random sequences on Synopsys VCS; caught four RTL bugs including a counter width error that silently disabled starvation prevention
- Verified grant correctness, arbitration fairness, and starvation prevention across 300 constrained-random transactions with zero scoreboard errors

---

## Technical Skills

| | |
|---|---|
| **Languages** | SystemVerilog, Verilog, Python, C |
| **Digital Design** | RTL Design, Parameterizable RTL, Pipeline Architecture, CDC, Bus Arbitration, Logic Synthesis |
| **Verification** | UVM 1.2, Constrained-Random Verification, Scoreboard Development, Waveform Debugging, Synopsys VCS |
| **Tools** | Yosys, Icarus Verilog, GTKWave, Synopsys VCS, EDA Playground, Git, Linux |

---

## Education

**University of California, Davis**  
MS, Electrical and Computer Engineering *(expected March 2028)*  
Graduate Coursework (Planned): High Performance Computer Architecture, Advanced Verification, IC Design & Tapeout, Hardware Security, Deep Learning Hardware

**University of San Francisco**  
BS, Computer Science, Cum Laude  
Dean's List · 4 semesters

---

## What I'm Working Toward

I'm targeting ASIC/RTL engineering and digital verification internships at companies working on high-performance silicon, processors, accelerators, and interconnects. My background in CS gives me strong footing in computer architecture; my portfolio projects are closing the gap toward industry-ready digital design and verification skills.

Open to internship opportunities starting **Summer 2027**.

---

📂 [GitHub](https://github.com/mvvillarrealblozis) · 💼 [LinkedIn](https://www.linkedin.com/in/maximilianovb/?skipRedirect=true) · ✉️ [maxvblozis@gmail.com](mailto:maxvblozis@gmail.com)
