
# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
MOV A,P0 
MOV R0,A 
MOV B,R0 
MUL AB 
MOV P2,A 
END









```

## OUTPUT
<img width="1230" height="596" alt="Screenshot 2025-11-11 183032" src="https://github.com/user-attachments/assets/64399fa4-1c1d-4649-93a0-18a8835756a2" />

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```

ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END









```


## OUTPUT
<img width="1259" height="569" alt="Screenshot 2025-11-11 183010" src="https://github.com/user-attachments/assets/dbf104e7-4743-4f23-908c-cddd4b1e893c" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
