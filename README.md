<!--
Meta: description="MiniOS — a lightweight process scheduling simulator in C demonstrating FCFS, SJF, Priority, and Round Robin algorithms for operating systems coursework." keywords="process scheduling, scheduling algorithms, FCFS, SJF, Round Robin, priority scheduling, operating systems simulator, C program, GCC, MinGW"
-->

# MiniOS — Process Scheduling Simulator (C)

MiniOS is a compact process scheduling simulator implemented in C for learning and demonstrating operating systems scheduling algorithms. It supports FCFS (First-Come, First-Served), SJF (Shortest Job First), Priority Scheduling, and Round Robin. This repository is ideal for students, instructors, and developers experimenting with scheduling strategies and visualizing basic scheduler behavior.

## Table of Contents
- [Features](#features)
- [Supported Algorithms](#supported-algorithms)
- [Demo](#demo)
- [Build & Run](#build--run)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Features
- Educational, easy-to-read C implementation.
- Interactive CLI to add processes and select scheduling algorithms.
- Supports: FCFS, SJF, Priority Scheduling, Round Robin (with configurable quantum).
- Minimal dependencies — builds with `gcc`/MinGW on Windows and `gcc` on Unix-like systems.

## Supported Algorithms
- First-Come, First-Served (FCFS)
- Shortest Job First (SJF)
- Priority Scheduling
- Round Robin (RR) — configurable time quantum

## Demo
Build and run locally to see scheduling choices and turnaround/waiting time calculations.

## Build & Run
Prerequisites: `gcc` (MinGW on Windows or GCC on Linux/macOS)

To compile:

```powershell
gcc PROJECTWORK.c -o PROJECTWORK.exe
```

To run:

```powershell
./PROJECTWORK.exe
```

## Usage
1. The program prompts whether to add processes; enter `Y` to add or `N` to skip.
2. Enter process arrival time, burst time, and priority when requested.
3. Choose an algorithm from the menu (enter the number corresponding to the algorithm).
4. For Round Robin, you will be prompted to enter the time quantum.

The simulator prints scheduling order and basic metrics such as waiting time and turnaround time for each process.

## Examples
Example compile and run:

```powershell
gcc PROJECTWORK.c -o PROJECTWORK.exe
./PROJECTWORK.exe
# Follow prompts to add processes and choose an algorithm
```

Keywords for discoverability: process scheduling simulator, scheduling algorithms in C, FCFS, SJF, Round Robin, priority scheduling, operating systems lab.

## Contributing
- Feel free to open issues or submit pull requests to improve documentation, add new scheduling policies, or add automated tests.

## License
This repository does not include a license file. Add a `LICENSE` if you wish to permit reuse.

## Contact
For questions or help, raise an issue in this repository.
