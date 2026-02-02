# Scan Insertion and ATPG using Fault (Open Source)

## Objective
To perform Design-for-Testability (DFT) analysis, scan insertion, scan cut, and ATPG-based fault coverage evaluation of a 4-bit counter using open-source tools.

## Tools Used
- Yosys (RTL synthesis)
- Fault (Scan insertion, scan cut, ATPG)
- osu035 standard cell library

## Flow
1. RTL design of counter
2. Synthesis using Yosys
3. Scan chain insertion using Fault
4. Scan cut for ATPG preparation
5. ATPG and fault simulation
6. Fault coverage analysis

## Results
- Stuck-at fault coverage: ~86.56%
- Test vectors generated in JSON and SVF formats

## Technology
- osu035 (0.35 µm open PDK)

