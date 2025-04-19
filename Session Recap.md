# Introduction

> CPU performance factors

- Instruction counts
- CPU clock speed

### Instruction Classes
1) Arithmetic-logic Instructions: 
2) Memory Load and Store instructions
3) Control transfer instructions

#### Arithmetic-logic
Performs arithmetic logic instructions
> like add, sub, and, andi.

Loads and Stores instructions: Load data from memory to register and store data from register to memory

#### Load and Store

??

performs load and store for items:

```c
double A[N];
a[12] = h + a[8];
```

#### Conditional Branch

- conditional
```asm
beq rs1, rs2, L1
```
`if rs1 == rs2` jump to `L1`

- unconditional
```asm
beq x0, x0, L1
```
jump to `L1` regardless

> Instruction and Data
> It is  up to the CPU to interpret and store integers in binary or not

```asm
add x9,x20,x21
```


#### Format Encoding for Branch

Branch Instructions specify:
- Opcode, 2 registers, target address

SB format instructions: `beq x8,x9,4`

**It cannot assign to odd bits (like 4 is fine but 3 is not)**



