# Tiny Stack VM

[![Tiny Stack VM](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![Rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Bounty-hun/tiny-stack-vm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![Reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Bounty-hun/tiny-stack-vm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

A tiny stack virtual machine for the [make.fun](https://make.fun) bounty
`tiny-stack-vm-01-run-20261122`: it runs 40 tiny-stack ISA programs per set
and answers each with its exact output bytes and exit code.

`main.ts` (Node 22) is a faithful port of the kit's reference VM — 32-bit
wrapping values, 256-value stack, 64-deep call stack, 256 words of memory,
and all ten trap codes with the step and output limits. One rule for every
program, deterministic: no clock, no network, no environment as variation.
