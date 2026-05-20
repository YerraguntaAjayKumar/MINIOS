MiniOS - Process Scheduling Simulator

Summary
- Simple process scheduling simulator in C supporting FCFS, Priority, SJF, and Round Robin.

Files
- PROJECTWORK.c : Source code implementing multiple scheduling algorithms.
- PROJECTWORK.exe, PROJECTWORK.o : Compiled artifacts (may be from previous builds).

Build (requires GCC/MinGW on Windows):

To compile:

```powershell
gcc PROJECTWORK.c -o PROJECTWORK.exe
```

Run:

```powershell
./PROJECTWORK.exe
```

Usage
- The program interactively asks whether you want to add processes. Enter `Y` to add or `N` to skip.
- After entering processes, choose a scheduling algorithm (1-4) when prompted.

Notes
- Round Robin will prompt for a time quantum if zero is provided.
- If you don't have `gcc`, install MinGW or use an alternative C compiler.
