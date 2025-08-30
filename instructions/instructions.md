# Instruction Set of 8086 intel

# Arithmetic

# Addition

### 1) ADD

Operand1=operand1+operand2;

Usage:

MOV AL, 3

ADD AL, 7

RET

⇒ AL=000A

Note: Source and Destination cant be Memory.

### 2) ADC

Operand1=operand1+operand2+CF

Usage: 

MOV AL,5

ADD AL,1  ; ⇒ AL=7 if cf is set

### 3) AAA

ASCII after addition

### 4) AAS

### 5) AAM

# Subtraction

### 1) SUB

Working: operand1=operand1-operand-CF

SUB AX, BX

The result is stored in AX

### 2) SBB

## Inc/Dec

### INC

### DEC

# Multiplication

## Division