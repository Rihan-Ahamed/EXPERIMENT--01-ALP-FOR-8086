# EXPERIMENT--01-ALP-FOR-8086
Name :
Roll no 
Date of experiment :





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

## Addition  of 16 bit ALP 
~~~
Mov AX,1072H
MOV BX,3452H
ADD AX,BX
HLT
~~~



## Output  
 <img width="1381" height="1108" alt="Screenshot 2026-05-22 153942" src="https://github.com/user-attachments/assets/d2704ca5-1a84-4c12-bd2f-f7dd0455bf06" />

## Subtraction   of 8 bit numbers  ALP 
 ~~~
Mov AX,1072H
MOV BX,3452H
SUB AX,BX
HLT
~~~
## Output  
<img width="1394" height="1090" alt="Screenshot 2026-05-22 154102" src="https://github.com/user-attachments/assets/5ca98082-19db-4d87-8a44-9041f1567c75" />

## Multiplication alp 
~~~
Mov AX,1072H
MOV BX,3452H
MUL BX
HLT
~~~
 ## Output  
<img width="1388" height="1081" alt="Screenshot 2026-05-22 154351" src="https://github.com/user-attachments/assets/8695cd6f-e565-434c-bce8-46fabdb06f30" />


## Division alp 
~~~
Mov AX,1072H
MOV BX,3452H
DIV BX
HLT
~~~
## Output  
<img width="1388" height="1084" alt="Screenshot 2026-05-22 154512" src="https://github.com/user-attachments/assets/51b18b18-4197-4f5f-ad6a-2fc0ffdad563" />

## AND alp
~~~
Mov AX,1072H
MOV BX,3452H
AND AX,BX
HLT
~~~
## output

<img width="1390" height="1082" alt="Screenshot 2026-05-22 154947" src="https://github.com/user-attachments/assets/4e941c84-dbba-46f3-a59f-2a74346bcaef" />


## NAND alp
~~~
Mov AX,1072H
NOT AX
HLT
~~~
## output
<img width="1397" height="1081" alt="Screenshot 2026-05-22 155120" src="https://github.com/user-attachments/assets/d74f40f7-e39d-4c7a-a345-f8ff7c70ad03" />

## OR alp
~~~
Mov AX,1072H
MOV BX,3452H
OR AX,BX
HLT
~~~

## output
<img width="1417" height="1080" alt="Screenshot 2026-05-22 154703" src="https://github.com/user-attachments/assets/e2f3767e-01fd-4e8e-a83b-35e21d86e0d1" />

## XOR alp
~~~
Mov AX,1072H
MOV BX,3452H
XOR AX,BX
HLT
~~~

## output
<img width="1389" height="1066" alt="Screenshot 2026-05-22 154827" src="https://github.com/user-attachments/assets/737204c9-f491-429f-8aad-c88571df44ea" />


## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
 








