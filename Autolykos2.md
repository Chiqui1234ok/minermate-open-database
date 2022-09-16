Shown hashrate are always **per card**.

# PC-RIGOBERTA (RTX 3070Ti x1)
## ERGO

- Core 1500MHz
- Mem +1750MHz
- Lock cv N/D
- Fan target 94c[50-90] (mem)
- Watts 150W
- 170MH/s

# PC-RIGOBERTA (RTX 3080Ti x1)
## ERGO

- Core 1400MHz
- Mem +1400MHz
- Lock cv N/D
- Fan target 94c[40-90] (mem)
- Watts 220W
- 239,5MH/s

# PC-RIGOBERTA (RX 6900 XT x1 + RX 6800)
## ERGO

- Core 1500MHz
- Mem 2130MHz
- Lock cv 700mv
- Fan target 60c[40-90]
- Watts 120W
- 124MH/s

# PC-HERMES-MINI (GTX 1660Ti x3)
## ERGO

- Core 1300MHz
- Mem +1100MHz
- Lock cv N/D
- Fan target 64c[30-90]
- Watts 66W
- 59,3MH/s

# PC-HERMES-MINI (RTX 3060 x1)
## ERGO

- Core 1600MHz
- Mem +1200MHz
- Lock cv N/D
- Fan target 64c[40-90]
- Watts 105W
- 124MH/s

# PC-PHANTOM (RX 5600 XT x5, ETH bios mod)
## ERGO

- Core 1200MHz
- Mem 1800MHz
- Lock cv 720
- Fan target 94c (mem)
- Watts 95W
- 80,5MH/s

# PC-FLORIDA6 (RTX 3070 x4)
## ERGO

- Core 1450MHz
- Mem +1300MHz
- Lock cv N/D
- Fan target 64c[30-90]
- Watts 110W
- 163MH/s

```bat
@echo off
REM "Kucoin ERGO wallet"
cd "C:\Mining\t-rex"
:trex
t-rex.exe -a autolykos2 -o stratum+tcp://de.ergo.herominers.com:1180 -u 9hryTqEYCVLRobqoEcEfRwgMBHWaYGg8Gfv2gcjxnt7oLmY5z49.PC-FLORIDA6 -p x --lock-cclock 1450,1450,1450,1450 --mclock +1300,+1300,+1300,+1300 --fan t:64[30-90],t:64[30-90],t:64[30-90],t:64[30-90]
goto trex
```