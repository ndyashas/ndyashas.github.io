---
layout: project

title: Salaga-RV
github: https://github.com/ndyashas/Salaga-RV
metacontent: RISC-V,RISCV,CPU,RTL,Verilog,Syetm-Verilog,System Verilog,RTL-Design,Computer-Architecture,CPU-Design,Computer Architecture,CPU Design,

bgimage: Salaga/banner.png
icimage: Salaga/banner.png
---

## Salaga family of RISC-V Cores
Salaga family of RISC-V processors all support the `rv32i` instruction set. All the programs are written in System Verilog, and are simulated using Verilator.

The main purpose of me writing these cores is to implement from scratch what was taught to me in the EE-457 course at USC by [Prof. Gandhi Puvvada](https://viterbi.usc.edu/directory/faculty/Puvvada/Gandhi). The different cores are:

#### Eka
*Eka* core is a Single Cycle CPU. Ofcourse, this core is not practical for implementation. However, it is a great way of familiarizing oneself with the instruction set and basic architecture for a 5 stage CPU.

The core interface is as shown below
<div class="row gtr-50 gtr-uniform">
     <div class="col-12"><span class="image fit"><img src="/images/Salaga/Eka/core-interface.png" alt="core-interface" /></span></div>
</div>
