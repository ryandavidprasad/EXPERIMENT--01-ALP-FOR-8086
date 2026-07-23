# EXPERIMENT--01-ALP-FOR-8086
# Name : Ryan David Prasad
# Roll no : 212224040282
# Date of experiment : 23/07/2026

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
## Output :
# ADDITION
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
add ax,bx
mov [1200h], ax
mov [1202h], dx
hlt
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/713a8d52-ecd0-49a1-ad72-48b5f8b86d4c" />

# SUBRACTION
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
sub ax,bx
mov [1200h], ax
mov [1202h], dx
hlt
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/e40365a2-24bb-4d33-ab7a-ac02c61b6678" />

# MULTIPLICATION
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
mul bx
mov [1200h], ax
mov [1202h], dx
hlt
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/95e0147d-a73e-4531-b2f8-ee12c153641e" />

# DIVISION
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
div bx
mov [1200h], ax
mov [1202h], dx
hlt
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/c4f016a3-7f62-446a-829f-8611b037a851" />

# AND
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
and ax,bx
ret
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/115a01a4-8c97-4a35-b8c0-90fc5ab46a04" />

# OR
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
or ax,bx
ret
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/2862f2d0-75ed-4849-bdae-59f44e13e0ed" />

# NAND
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
and ax,bx
not ax
ret
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/494397c6-c09e-4a47-8f1c-163f6b3b4e82" />

# NOR
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
or ax,bx
not ax
ret
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/9325eee5-7f6c-40e5-8dbd-47d68a368251" />

# XOR
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
xor ax,bx
ret
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/da96b723-2ce2-4ff3-b28b-1e66302b1a97" />

# XNOR
```
org 100h
mov ax,[1100h]
mov bx,[1102h]
xor ax,bx  
not ax
ret
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/50d303d5-07f8-45fc-8228-9569f657b8be" />

# NOT
```
org 100h
mov ax,[1100h]  
not ax 
ret
```
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/2e2b7cdb-255b-43eb-9106-d3738f9c2be8" />


## Result :
Thus execution of ALP on fundamental arithmetic and logical operations is sucessfully verified.
