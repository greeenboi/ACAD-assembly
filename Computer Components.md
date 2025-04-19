## Program counter
Program instructions and data are all stored in memory.
PC is a register that stores the address of the instruction the process is executing.

#### Instruction Execution

1) Processor fetches an instruction word from instruction memory.
2) The instruction word is decoded to know the source (register number), and then registers are read to have source operans ready
3) Data is taken to ALU, 
4) LW | SW for memory access
5) then result is written to register

#### Register Files

- Reads are combinational
  Can read in any cycle and for multiple reads


![[Drawing 2025-04-19 12.06.57.excalidraw]]
