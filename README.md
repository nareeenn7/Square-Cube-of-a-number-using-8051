# Square-Cube-of-a-number-using-8051
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
<img width="427" height="241" alt="image" src="https://github.com/user-attachments/assets/dab0f143-c341-43a8-9b53-3af93b64d214" />


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


OV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END






```


## OUTPUT
<img width="313" height="228" alt="image" src="https://github.com/user-attachments/assets/c2cec861-7bee-49dd-ab89-7b20039f7f8d" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


