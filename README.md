
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
<img width="1230" height="596" alt="image" src="https://github.com/user-attachments/assets/76b954f9-827e-4663-99b9-3269aac3e525" />


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
<img width="1259" height="569" alt="image" src="https://github.com/user-attachments/assets/aa7e5e30-5acb-43d4-9ca5-396d49aab48b" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
