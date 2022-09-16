Shown hashrate are always **per card**.

# PC_FRANCO5 (RTX 3070 x6), PC_FRANCO4 (RTX 3070 x5)
## RVN

- Core 1300MHz
- Mem +1200MHz
- Lock cv N/D
- Fan target 60c
- Watts 156W
- 30,4MH/s

# PC_FRANCO3 (RTX 2060 x5), PC_FRANCO2 (RTX 2060 x5)
## RVN

- Core 1700MHz
- Mem +950MHz
- Lock cv 720mv
- Fan target 64c[30-90]
- Watts 150W
- 17,94MH/s

```bat
@echo off
REM "Port 16057 over SSL, 16059 HTTP"
cd "C:\Mining\t-rex"
:start
t-rex -a kawpow -o stratum+tcp://rvn-eu.minerpool.org:16059 -u RGFQB4boAfvmvBUrzpv5cfrLDu9aaVWfod.PC_FRANCO3 -p franco22 --pl 84,84,84,84,84 --cclock +120,+120,+120,+120,+120 --mclock +950,+950,+950,+950,+950 --fan t:64[30-90],t:64[30-90],t:64[30-90],t:64[30-90],t:64[30-90]
goto start
```

# PCFRANCO1 (RTX 3070 x4)
## RVN

- Core 1300MHz
- Mem +1200MHz
- Lock cv N/D
- Fan target 64c[30-90]
- Watts 147W
- 30MH/s

---

# PC-3060Ti
## RVN

- Core 1400MHz
- Mem +1100MHz
- Lock cv N/D
- Fan target 64c[30-90]
- Watts 158W
- 29,75MH/s

### Example 👇

```bat
@echo off
REM "Port 16057 over SSL, 16059 HTTP"
cd "C:\Mining\t-rex"
:start
t-rex -a kawpow -o stratum+tcp://rvn-us-east.minerpool.org:16059 -u RTQvCyFLqpS2enva2FPHg6qi1KRKYdPsWi.PC-3060Ti -p minermate22 --lock-cclock 1400,1400,1300,1400 --mclock +1200,+1200,+1100,+1200 --fan t:64[30-90],t:64[30-90],t:64[30-90],t:64[30-90]
goto start
```

# PC-3070 (RTX 3070 x4), PC-3070-MK2 (RTX 3070 x2)
## RVN

- Core 1200MHz
- Mem +1000MHz
- Lock cv N/D
- Fan target 64c[30-90]
- Watts 147W
- 29,7MH/s

### Example 👇

```bat
@echo off
REM "Port 16057 over SSL, 16059 HTTP"
cd "C:\Mining\t-rex"
:start
t-rex -a kawpow -o stratum+tcp://rvn-us-east.minerpool.org:16059 -u RTQvCyFLqpS2enva2FPHg6qi1KRKYdPsWi.PC-3070 -p minermate22 --lock-cclock 1300,1300,1300,1300,1300,1300 --mclock +1100,+1100,+1100,+1100,+1000,+1100 --fan t:64[30-90],t:64[30-90],t:64[30-90],t:64[30-90],t:64[30-90],t:64[30-90]
goto start
```

# PC-3070 (RTX 3070 x4), PC-3070-MK2 (RTX 3070 x2)
## SERO

- Core 1200MHz
- Mem +1000MHz
- Lock cv N/D
- Fan target 64c[30-90]
- Watts 0W
- 29,3MH/s

---

