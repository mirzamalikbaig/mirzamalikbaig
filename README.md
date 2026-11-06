# Agha Malik Baig Mirza

Design verification and RTL. I'm finishing an M.S. in Computer Engineering at California State University, Northridge (December 2026), and I'm looking for full-time Design Verification and RTL roles starting January 2027.

[Portfolio](https://mirzamalikbaig.github.io/) · [Resume (PDF)](https://mirzamalikbaig.github.io/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/mirzamalikbaig)

## What I work on

SystemVerilog and UVM testbenches that check a design on their own: scoreboards, functional coverage, and assertions, mostly around AMBA APB and AXI4.

## Projects

- **[axi4_uvm](https://github.com/mirzamalikbaig/axi4_uvm)**: UVM environment for a memory-mapped AXI4 slave covering all five channels. Scoreboard with a reference memory, functional coverage, constrained-random stimulus, and SVA checks. The recorded VCS run reached 98.15% functional coverage with 0 UVM errors across 12 directed scenarios.
- **[apb_uvm](https://github.com/mirzamalikbaig/apb_uvm)**: an AMBA APB memory slave and a UVM environment around it: a directed sequence, a reference-memory scoreboard, and functional coverage. Run in Synopsys VCS.
- **[async_fifo](https://github.com/mirzamalikbaig/async_fifo)**: a 16-entry, 8-bit asynchronous FIFO with Gray-coded pointers and two-flop synchronizers, checked by a scoreboard, six SVA checks, and seven directed tests in Verilator. A learning project about clock domain crossing.
- **[memory_verification](https://github.com/mirzamalikbaig/memory_verification)**: a class-based SystemVerilog testbench for a synchronous memory, with a generator, driver, monitor, scoreboard, and coverage.

## Toolbox

- **Languages:** SystemVerilog, Verilog, Python, C
- **Tools:** Synopsys VCS, DVE, QuestaSim/ModelSim, Verilator, Xilinx Vivado, GTKWave, Git
- **Verification:** UVM, constrained-random and directed testing, coverage-driven verification, SystemVerilog Assertions
- **Protocols:** AMBA APB, AXI4, FIFOs, clock domain crossing basics

## Experience

- Verification Intern, Aisemi Pvt. Ltd. (Jan to Apr 2024): SystemVerilog RTL and testbenches, simulation and waveform debugging with Synopsys tools.
- Industrial Trainee, Electronics Corporation of India Limited (Nov 2019 to Mar 2020): supervised circuit testing and basic hardware troubleshooting.

More detail on each project is on the [portfolio](https://mirzamalikbaig.github.io/). I'm happy to walk through any of these testbenches.
