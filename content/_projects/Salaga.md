---
layout: project

title: Salaga-RV
github: https://github.com/ndyashas/Salaga-RV
metacontent: RISC-V,RISCV,CPU,RTL,Verilog,Syetm-Verilog,System Verilog,RTL-Design,Computer-Architecture,CPU-Design,Computer Architecture,CPU Design,

bgimage: Salaga/banner.png
icimage: Salaga/banner.png
---

## Salaga family of RISC-V Cores
Salaga family of RISC-V processors support the `rv32i` instruction set.

The purpose of this project is to implement what I learnt in USC's EE356, EE457, and EE402 classes by [Prof. Marco Paolieri](https://qed.usc.edu/paolieri/), [Prof. Gandhi Puvvada](https://viterbi.usc.edu/directory/faculty/Puvvada/Gandhi), and [Prof. Bill Cheng](http://merlot.usc.edu/william/usc/) respectivly.

I want to setup a stack where I can run a bare-metal ray-tracer program on my hardware cores. I plan to work on the following cores at the moment:

- **Eka**: Single-cycle design.
- **Jala**: 5-stage pipelined design.

All the cores share the same interface as shown below
<div class="row gtr-50 gtr-uniform">
     <div class="col-12"><span class="image fit"><img src="/images/Salaga/Salaga-core-interface.jpg" alt="core-interface" /></span></div>
</div>


### Cores:

#### Eka
[*Eka*](https://github.com/ndyashas/Salaga-RV/tree/main/RTL/Eka) core is a Single Cycle CPU. Implementing *Eka* was crucial for me to learn about the RISC-V ISA, as well as a good starting point for implementing *Jala*.

#### Jala
*Jala* is still a work in progress and will be a 5-stage in-order pipelined CPU.
