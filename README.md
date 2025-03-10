 # EXPERIMENT--01-ALP-FOR-8086
### Name :NAVEEN.S
### Roll no :212223240106
### Date of experiment :07.03.2025





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
Mov Al, 97H
Mov Bl, 36H
Add Al,Bl
Hlt
```


## Output  
![Screenshot (175)](https://github.com/user-attachments/assets/ee77b486-affc-4423-83da-1e6b7e51bac9)

 
## Subtraction   of 8 bit numbers  ALP 
```
Mov Al, 69H
Mov Bl, 39H
Sub Al,Bl
Hlt
```
 
## Output  
![Screenshot (177)](https://github.com/user-attachments/assets/a855fec0-4d62-41fc-ba3e-96debca6d887)

## Multiplication alp 
```
Mov Al, 69H
Mov Bl, 39H
Mul Bl
Hlt
```
 ## Output  

![Screenshot (178)](https://github.com/user-attachments/assets/2699a130-0ada-444d-90cb-7eeecd217942)

## Division alp 
```
Mov Al, 69H
Mov Bl, 39H
Div Bl
Hlt
```

## Output  
![Screenshot (179)](https://github.com/user-attachments/assets/f8b0c4e7-5b58-427c-add6-dafeca4ea40d)



## Programs for logical operatioins
## Not alp:
```
MOV AL, 56H
MOV BL, 34H
NOT BL
HLT
```
## OUTPUT

![Screenshot (186)](https://github.com/user-attachments/assets/f46fef6d-e0a8-4a6f-94c0-315bdea12c3f)


## Xor alp:
```
MOV AL,48H
MOV BL,74H
XOR AL,BL
HLT
```

## OUTPUT:
![Screenshot (182)](https://github.com/user-attachments/assets/98eeda84-6b86-4afd-991c-861e71d66641)


## And alp:
```
MOV AL,59H
MOV BL,39H
AND AL,BL
HLT
```

## OUTPUT:
![Screenshot (180)](https://github.com/user-attachments/assets/3cb677b6-cf61-4751-ab73-5193ec2402e4)

## NOR alp
```
MOV AL,53H
MOV BL,32H
NOR AL,BL
HLT
```
## OUTPUT

![Screenshot (181)](https://github.com/user-attachments/assets/b9d0435c-a26f-43b4-9e02-a2af94266644)





## Result :
Thus the execution of ALP on fundamental arithmetic and logical operation has been performed successfully.


 










 
## Subtraction   of 8 bit numbers  ALP 
```
Mov Al, 69H
Mov Bl, 39H
Sub Al,Bl
Hlt
```
 
## Output  
![Screenshot (177)](https://github.com/user-attachments/assets/a855fec0-4d62-41fc-ba3e-96debca6d887)

## Multiplication alp 
```
Mov Al, 69H
Mov Bl, 39H
Mul Bl
Hlt
```
 ## Output  

![Screenshot (178)](https://github.com/user-attachments/assets/2699a130-0ada-444d-90cb-7eeecd217942)

## Division alp 
```
Mov Al, 69H
Mov Bl, 39H
Div Bl
Hlt
```

## Output  
![Screenshot (179)](https://github.com/user-attachments/assets/f8b0c4e7-5b58-427c-add6-dafeca4ea40d)



## Programs for logical operatioins
## Not alp:
```
MOV AL, 56H
MOV BL, 34H
NOT BL
HLT
```
## OUTPUT

![Screenshot (186)](https://github.com/user-attachments/assets/f46fef6d-e0a8-4a6f-94c0-315bdea12c3f)


## Xor alp:
```
MOV AL,48H
MOV BL,74H
XOR AL,BL
HLT
```

## OUTPUT:
![Screenshot (182)](https://github.com/user-attachments/assets/98eeda84-6b86-4afd-991c-861e71d66641)


## And alp:
```
MOV AL,59H
MOV BL,39H
AND AL,BL
HLT
```

## OUTPUT:
![Screenshot (180)](https://github.com/user-attachments/assets/3cb677b6-cf61-4751-ab73-5193ec2402e4)

## NOR alp
```
MOV AL,53H
MOV BL,32H
NOR AL,BL
HLT
```
## OUTPUT

![Screenshot (181)](https://github.com/user-attachments/assets/b9d0435c-a26f-43b4-9e02-a2af94266644)





## Result :
Thus the execution of ALP on fundamental arithmetic and logical operation has been performed successfully.


 








