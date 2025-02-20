# Assembly Memory Access Bug

This repository demonstrates a common error in assembly programming: accessing memory outside allocated bounds or attempting to write to read-only memory.

The `bug.asm` file contains code exhibiting this problem.  The `bugSolution.asm` shows a corrected version with better bounds checking.  Carefully review the code to understand the potential causes of segmentation faults and how to address them.