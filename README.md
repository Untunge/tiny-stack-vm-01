# tiny-stack-vm-01

A tiny stack virtual machine for make.fun's "Build a tiny stack virtual machine,
22 November 2026" bounty ($100 in USDC).

`main.ts` (Node 22) is a faithful implementation of the kit's tiny stack ISA
(`generator/subject/ISA.md`): 32-bit wrapping arithmetic, a 256-value stack,
64-deep call stack, 256 words of memory, input/output, and all ten traps with
their exact exit codes. It answers all 40 instances of a set in one run,
writing `/output/<id>/stdout.bin` and `/output/<id>/exit.txt` per instance.

Scores 1,000,000 (40/40 instances, full marks) on the kit's practice set.
