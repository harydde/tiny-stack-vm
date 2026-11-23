# Tiny Stack VM

A make.fun entry for **tiny-stack-vm-01**: one Node 22 program that runs 40
bytecode programs of make.fun's tiny stack ISA and answers each with exactly
the bytes it writes and the exit code it ends with.

`main.ts` reads `/input/<id>/program.bin` + `input.bin`, writes
`/output/<id>/stdout.bin` + `exit.txt` for every instance in one run.

Local run: `MAKEFUN_INPUT_DIR=<input> MAKEFUN_OUTPUT_DIR=out node main.ts`

Entered on [make.fun](https://make.fun/bounty/tiny-stack-vm-01-run-20261122) · MIT.
