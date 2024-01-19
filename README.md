# Pocket Programmer
Program the RCX on the RCX using its own screen and buttons.

**Original Website**: [Lego RCX Pocket Programmer](https://www.navina.ch/workshop/rcx/rcx.html)

&nbsp;

### The Yellow Lego RCX Brick
```
+-------------------------+ 
|View    1   2   3    Prgm| 
|[__]  +-----------+  [__]| 
|      | 00.PA   [ |	  | 
|OnOff +-----------+  Run | 
|[__]    A   B   C    [__]| 
+-------------------------+
```

The idea is based on "OnScreen" Copyright © 1999 by David R. van Wagner, and "LegOS 0.2.4" Copyright © 1998 by Markus L. Noga.

However, the code (firmware) for the Lego "RCX Pocket Programmer" has been completely rewritten to provide much more and enhanced functionality.

Unfortunately, unlike [OnScreenProgramming](https://github.com/BrickBot/OnScreenProgramming), the source code for this Pocket Programmer is not currently available, but available binaries are posted under Releases.

## Features:
* RCX Standalone/Pocket Programmer with 256 Program Steps
* 22 Powerful RCX Commands (GOto, PAUSe, INput, OUput, LOop, ...)
* 16 Registers (8-bit) for processing input/output data, etc.
* 20 Register Operations (LDD/STD/IN/OUT..ADD/SUB/MUL/DIV..AND/OR..)
* Conditional Branching (BEQ/BNE/BCC/BHI/BLO...)
* Subroutines (JSR/RTS)
* 256 Byte Memory Area (for User Variables/Data)
* Single Step Execution Mode
* VLL Communication (send VLL codes to MicroScout & CodePilot)
* IR Communication (send/receive Messages & Remote Commands)
