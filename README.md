# ARITHMETIC-LOGIC-UNIT-ALU-
COMPANY:COTECH IT SOLUTIONS PVT.LTD
NAME:GudipalliMounika
INTERN ID:CT12GUG
DOMAIN NAME: VLSI
BATCH DURATION:January 20th,2025 to March 20th,2025
MENTOR NAME:NEELA SANTHOSH

DESCRIPTION:In this i used Online eda as a software to write and run the code.The ALU performs various arithmetic and logical operations based on a 3-bit opcode. The testbench verifies its functionality with different test cases.The ALU module takes two 4-bit inputs (A, B) and a 3-bit opcode (opcode) to determine the operation. It produces a 4-bit result (result), a carry-out flag (carry_out), and a zero flag (zero).
Inputs:
A (4-bit): First operand.
B (4-bit): Second operand.
opcode (3-bit): Determines the operation to be performed.
Outputs:
result (4-bit): Stores the result of the operation.
carry_out (1-bit): Indicates if there's a carry/borrow in addition/subtraction.
zero (1-bit): Set to 1 if result is 0, otherwise 0.
-Uses an always @(*) block for combinational logic.
-Handles carry/borrow correctly by extending operands to 5-bits for subtraction.
-Zero flag is set when result is 0000.
ALU Testbench (ALU_tb)
-The testbench verifies the ALU's behavior by applying different inputs and monitoring outputs.
Components:
Registers (A, B, opcode) are used to apply inputs.
Wires (result, carry_out, zero) capture ALU outputs.
Instantiation of ALU Module connects testbench signals to the ALU.
Monitoring Output:
Uses $monitor to print signals dynamically.
Ends simulation with $finish.
