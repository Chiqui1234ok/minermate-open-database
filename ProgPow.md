Shown hashrate are always **per card**.

# PC-3070 (RTX 3070 x4), PC-3070-MK2 (RTX 3070 x2)
## SERO

- Core 1200MHz
- Mem +1000MHz
- Lock cv N/D
- Fan target 64c[30-90]
- Watts 0W
- 29,3MH/s

### Example 👇

```bat
@echo off
REM "Gate.io wallet (santiagogimenez@outlook.com.ar's account)"
cd C:\Mining\t-rex
:trm
t-rex -a progpow --coin sero -o stratum1+tcp://andromedapool.net:8008 -u fmDQCa7r5MHTktHS7SkcMznrG82avCfvp3BbqzdByAW798rX4iKz6q2yhywjb46chZjgBcfkg94BStaBS84RHFgW4eeLj9BTRaUpcwK4RMjwvwHNzhAGhopGHCtD4RT347u -w PC-3070 -p minermate22 --pl 68,68,68,68,68,68 --cclock +130,+130,+130,+130,+130,+130 --mclock +1050,+1050,+1050,+1050,+1050,+1050 --fan t:68[30-90],t:68[30-90],t:68[30-90],t:68[30-90],t:68[30-90],t:68[30-90]
goto trm
```