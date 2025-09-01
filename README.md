# EXPERIMENT--01-ALP-FOR-8086
## Name :S.AISHWARIYA

## Roll no: 212224240005

## Date of experiment :01.09.2025

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

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

## Addition  of 8 bit ALP 
```
MOV AL, 53H;

MOV BL, 24H;

ADD AL,BL;

HLT
```

## Output  
 <img width="1920" height="1080" alt="Screenshot 2025-08-19 142603" src="https://github.com/user-attachments/assets/6dcf52ee-3214-4c8b-971c-4171666c8531" />

## Subtraction   of 8 bit numbers  ALP 
 ``` MOV AL, 53H;
 
 MOV BL,24H;
 
 SUB AL,BL;
 
 HLT
 ```
## Output
<img width="1920" height="1080" alt="Screenshot 2025-08-19 142905" src="https://github.com/user-attachments/assets/564319f2-b481-423b-a645-9cd905bfd4e6" />

## Multiplication alp
``` MOV AL, 53H;

MOV BL, 24H;

MUL BL;

HLT
```
 ## Output  

<img width="1920" height="1080" alt="Screenshot 2025-08-19 143052" src="https://github.com/user-attachments/assets/9bb9fe93-024d-410e-bc1d-1bdd989bfba5" />

## Division alp 
``` MOV AL, 53H;

MOV BL, 24H;

DIV BL;

HLT
```
## Output  
<img width="1920" height="1080" alt="Screenshot 2025-08-19 143216" src="https://github.com/user-attachments/assets/b06fad69-50cf-40c8-9cc7-c62e7bdc6f04" />
 
## AND
```MOV AL, 53H;

MOV BL, 24H;

AND AL,BL;

HLT
```
## Output 
<img width="1920" height="1080" alt="Screenshot 2025-08-19 143356" src="https://github.com/user-attachments/assets/46a2fcfc-1440-49de-a812-b8ad490578c9" />
## OR
``` MOV AL, 53H;

MOV BL, 24H;

OR AL, BL;

HLT
```
## Output
<img width="1920" height="1080" alt="Screenshot 2025-08-19 143356" src="https://github.com/user-attachments/assets/b4f3ff36-b3a4-427e-ac8a-dfb022fae042" />

## NOT
``` MOV AL, 53H;

MOV BL, 24H;

NOT AL;

HLT
```
## OUTPUT
<img width="1920" height="1080" alt="Screenshot 2025-08-19 143442" src="https://github.com/user-attachments/assets/19132857-2066-4b5a-b711-a681485b36d5" />

## EX-OR
```
MOV AL, 53H;

MOV BL, 24H;

XOR AL, BL;

HLT
```
## OUTPUT
<img width="1920" height="1080" alt="Screenshot 2025-08-19 143544" src="https://github.com/user-attachments/assets/b9770076-e0e7-4cd3-93e0-87a7e9502b29" />

## Result :
 Thus ,ALP for fundamental arithmetic and logical operations are executed successfully.








