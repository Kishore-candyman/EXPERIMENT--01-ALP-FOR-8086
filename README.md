# EXPERIMENT--01-ALP-FOR-8086

**Name** : Kishore M

**Roll no** : 212224040161

**Date of experiment** : 21/07/2026


## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations

## Components required: 
8086  emulator 

## Theory:
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory

2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 

5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 

![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

9.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

## Addition of 16 bit number ALP:

```
MOV AX, 512AH
MOV BX, 7394H
ADD AX,BX
MOV [3001H],AX
HLT
```

## Output:

<img width="1917" height="1151" alt="add" src="https://github.com/user-attachments/assets/6bbfec0b-f80c-4573-8243-5d6b191bcfd6" />
 
## Subtraction of 16 bit number ALP:

 ```
MOV AX, 512AH
MOV BX, 7394H
SUB AX,BX
MOV [3003H],AX
HLT
```
## Output:

<img width="1918" height="1152" alt="sub" src="https://github.com/user-attachments/assets/be682177-7b7c-4d9f-b2af-69811cb24846" />

## Multiplication ALP:

```
MOV AX, 512AH
MOV BX, 7394H
MUL BX
MOV [3005H],AX
MOV [3007H],DX
HLT
```

## Output:

<img width="1918" height="1151" alt="mul" src="https://github.com/user-attachments/assets/eb59b2d9-a17c-4fdd-beba-58b15cf9aba2" />


## Division ALP:

```
MOV AX, 512AH
MOV BX, 7394H
DIV BX
MOV [3009H],AX
MOV [300BH],DX
HLT
```

## Output:

<img width="1918" height="1151" alt="div" src="https://github.com/user-attachments/assets/5995950c-2612-40a4-be6c-f935b861fd56" />

---
## Programs for logical operations (16 bit):

## AND operator:
```
MOV AX, 512AH
MOV BX, 7394H
AND AX,BX
MOV [4001H],AX
MOV [4003H],DX
HLT
```
## Output:

<img width="1918" height="1151" alt="AND" src="https://github.com/user-attachments/assets/a66a2d04-1bc9-4e83-9a63-4371cb37dc5f" />

## OR operator:
```
MOV AX, 512AH
MOV BX, 7394H
OR AX,BX
MOV [4005H],AX
MOV [4007H],DX
HLT
```
## Output:

<img width="1918" height="1151" alt="OR" src="https://github.com/user-attachments/assets/d8aa123a-6752-411b-b4a9-a1d2971d267a" />

## NOT operator:
```
MOV AX, 512AH
NOT AX
MOV [4009H],AX
HLT
```
## Output:

<img width="1918" height="1151" alt="NOT" src="https://github.com/user-attachments/assets/8e6c1043-ad73-4e76-98f3-0002dc048810" />

## XOR operator:
```
MOV AX, 512AH
MOV BX, 7394H
XOR AX,BX
MOV [4011H],AX
MOV [4013H],DX
HLT
```
## Output:

<img width="1912" height="1152" alt="XOR" src="https://github.com/user-attachments/assets/a05c9529-5a6f-4302-9ffb-0ea4f2a0b9ac" />

## Result :
 
Thus, the Assembly Level Program is executed successfully for both Arithmetic and Logical operators.







