## EXPERIMENT--01-ALP-FOR-8086

## Name : HEMANTH KUMAR R
## Roll no : 212223040065
## Date : 28/01/2026



## Aim: To Write and execute ALP for fundamental arithmetic and logical operations 8086
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

9.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below
11.	
![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations
## Addition of 8 bit ALP
~~~
Mov AL,74H
MOV BL,69H
ADD AL,BL
HLT
~~~
## Output  
<img width="773" height="415" alt="image" src="https://github.com/user-attachments/assets/07a7be9e-5404-4398-867e-b7b0f080d71b" />

## Subtraction   of 8 bit numbers  ALP 

~~~
Mov AL,74H
MOV BL,69H
SUB AL,BL
HLT
~~~
 
## Output  
<img width="770" height="390" alt="image" src="https://github.com/user-attachments/assets/bdc56e3b-5204-422f-b16a-1d12df1c42c4" />

## Multiplication alp 
~~~
Mov AL,74H
MOV BL,69H
MUL BL
HLT
ret
~~~

## Output  
<img width="773" height="399" alt="image" src="https://github.com/user-attachments/assets/63a26bc8-a63f-4945-b56d-eac5f954a8c3" />


## Division alp 
~~~
MOV AL,68H
MOV BL,18H
DIV BL
HLT
~~~
## Output 
<img width="780" height="397" alt="image" src="https://github.com/user-attachments/assets/a31a98e0-eb1e-46f8-846b-d4b182d7cc9f" />

## And of 8 bit numbers ALP
~~~
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
~~~

## OUTPUT
<img width="776" height="433" alt="image" src="https://github.com/user-attachments/assets/7740785b-7e9a-419e-904e-e5ace421c59b" />

## OR of 8 bit numbers ALP
~~~
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
~~~
 ## OUTPUT

 <img width="774" height="406" alt="image" src="https://github.com/user-attachments/assets/cc4e22c2-221a-454c-949b-5ece6dfb12ed" />

## NOT of 8 bit number ALP
~~~
MOV AL,65H
NOT AL
HLT
~~~
## OUTPUT

<img width="777" height="500" alt="image" src="https://github.com/user-attachments/assets/9cb50837-6c32-4c69-97a6-643a64c3623f" />

## XOR of 8 bit number ALP
~~~
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
~~~

## OUTPUT
<img width="770" height="592" alt="image" src="https://github.com/user-attachments/assets/4b798792-77cf-42c3-acab-5aa290862af5" />

## RESULT
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.

