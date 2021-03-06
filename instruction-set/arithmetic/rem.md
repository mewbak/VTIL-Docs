---
description: >-
  Performs an unsigned modulo operation on a register with a register or
  immediate value. The source value is represented by 2 registers for high and
  low bits.
---

# REM

| Instruction | Operand 1 | Operand 2 | Operand 3 | Description |
| :--- | :--- | :--- | :--- | :--- |
| REM | Reg | Reg/Imm | Reg/Imm | OP1 = \[OP2:OP1\] % OP3 |

```cpp
block->rem(vtil::REG_SP, 0, vtil::REG_SP); // sets REG_SP to 0
```

