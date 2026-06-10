# CIS-11-Final-Course-Project-
================================================================================
LC-3 TEST SCORE CALCULATOR
================================================================================

A modular LC-3 assembly program that automates academic metric processing. 
This application ingests five student test scores, computes the minimum, 
maximum, and average, and assigns a final letter grade.

--------------------------------------------------------------------------------
QUICK START
--------------------------------------------------------------------------------
1. Open the LC-3 Simulator (e.g., LC3Edit or PennSim).
2. Load ProjectCode1.asm.
3. Assemble and run the program.
4. Enter five test scores (0-100) when prompted.

--------------------------------------------------------------------------------
FEATURES
--------------------------------------------------------------------------------
- Automated Statistics: Calculates Min, Max, and Average in real-time.
- Grading Engine: Automatically maps averages to a standard A-F scale.
- Modular Architecture: Uses discrete subroutines (INPUT, CALC, GRADE, OUTPUT) 
  for clean, maintainable logic.
- Memory Safe: Implements a strict stack-based PUSH/POP policy to prevent 
  register clobbering.

--------------------------------------------------------------------------------
TECHNICAL SPECS
--------------------------------------------------------------------------------
- Memory Map: .ORIG x3000
- Data Storage: Contiguous 5-word array (.BLKW 5) accessed via pointer (R5).
- Arithmetic: Uses two's complement subtraction and iterative loop-based 
  division.
- I/O: Utilizes standard TRAP routines (x20, x21, x22) for terminal 
  interaction.

--------------------------------------------------------------------------------
PROJECT STRUCTURE
--------------------------------------------------------------------------------
- Section 1: Requirements and Design Philosophy.
- Section 2: Source Code (.asm).
- Section 3: Testing Data, Performance Analysis, and Roadmap.

--------------------------------------------------------------------------------
COMPLIANCE
--------------------------------------------------------------------------------
- Course: CIS11 – 22429
- Project Option: B (Test Score Calculator)
- Team: Beep-Boop (Ernie Gamez, Leonardo Garcia, D’von White)
================================================================================
