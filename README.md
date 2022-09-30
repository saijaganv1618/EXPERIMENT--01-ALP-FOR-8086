EXPERIMENT--01-ALP-FOR-8086


Name :Jagan A

Roll no : 212221230037

Date of experiment : 30/09/22

Aim:
To Write and execute ALP on fundamental arithmetic and logical operations

Components required:
8086 emulator

Theory :
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

Running the Emulator :
Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory

Run emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color .

 write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
Compile the program and check for the errors

Run (once there is no syntax error)

Click OK to see/view the output of your program on the Emulator screen.

After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,

<img width="527" alt="image" src="https://user-images.githubusercontent.com/59290560/193326225-5f6987af-99d3-4f0d-82fa-f15c55278473.png">


Click on emulate to start emulation

<img width="543" alt="image" src="https://user-images.githubusercontent.com/59290560/193326399-52f860ae-d0e5-439a-8a01-f55c378c6f72.png">

If no errors are found click on run the program and check the status of various flags in the flags tab as shown below
<img width="145" alt="image" src="https://user-images.githubusercontent.com/59290560/193326479-086d1db8-1e8d-4ec8-ba3e-0981dd14d8d6.png">

Programs for arithmetic operations
Addition of 8 bit ALP
name "ADDITION"
org 100h
MOV AH,05H;
MOV BH,02H;
ADD AH,BH;
MOV CH,AH;
MOV AH,0H; 
MOV BH,0H;
HLT;



Output
AH and BH registers for ADDITION
<img width="745" alt="image" src="https://user-images.githubusercontent.com/59290560/193326610-66a87f97-ac91-45a1-8523-d2d8e6b12b8f.png">


Performing 8 Bit ADDITION
<img width="749" alt="image" src="https://user-images.githubusercontent.com/59290560/193326681-d919342c-e663-4870-afdc-78c6eebdfb0c.png">


Moving to CH register
<img width="755" alt="image" src="https://user-images.githubusercontent.com/59290560/193326763-5d485b47-069a-4385-a6c8-5434d52fd18d.png">


Resetting AH,BH register and Execution
<img width="794" alt="image" src="https://user-images.githubusercontent.com/59290560/193326897-55094f83-0ee3-4669-9883-7c36cc4f2dda.png">


Flags:
<img width="86" alt="image" src="https://user-images.githubusercontent.com/59290560/193326962-44862002-6f24-4306-840a-85c0737374c0.png">


Subtraction of 8 bit numbers ALP
name "SUBTRACTION"
org 700h
MOV AH,7H;
MOV BH,5H;
SUB AH,BH;
MOV CH,AH;
MOV AH,0H;
MOV BH,0h;
HLT;


Output
AH and BH registers for SUBTRACTION
<img width="712" alt="image" src="https://user-images.githubusercontent.com/59290560/193327038-c105df86-8915-4b97-b460-13a705970a80.png">


Performing 8 Bit SUBTRACTION
<img width="704" alt="image" src="https://user-images.githubusercontent.com/59290560/193327102-0ea1519a-38d2-4a44-9598-46eaef8979ae.png">


Moving to CH register
<img width="704" alt="image" src="https://user-images.githubusercontent.com/59290560/193327181-22de04df-cde8-46ab-b5bb-630478b5b088.png">


Resetting AH,BH register and Execution
<img width="704" alt="image" src="https://user-images.githubusercontent.com/59290560/193327241-0d074471-63ca-4595-a73c-01172b3345e0.png">


Flags:
<img width="93" alt="image" src="https://user-images.githubusercontent.com/59290560/193327296-4bcd3dde-94a0-42ca-b06d-fa43340c2ae7.png">


Multiplication alp
name "MULTIPLICATION"
org 700h
MOV AX,5H;
MOV BX,4H;
MUL BX;
MOV CX,AX;
MOV AX,0H;
MOV BX,0h;
HLT;


Output
AX and BX registers for MULTIPLICATION
<img width="719" alt="image" src="https://user-images.githubusercontent.com/59290560/193327342-c3cb54a6-65d2-43f7-94a1-b61b09f4b683.png">


Performing 8 Bit MULTIPLICATION
<img width="707" alt="image" src="https://user-images.githubusercontent.com/59290560/193327379-4e51e52f-526c-4638-a206-e94c4fdbb147.png">


Moving to CX register
<img width="709" alt="image" src="https://user-images.githubusercontent.com/59290560/193327421-c8fd8cba-c8cc-4cf1-8324-1906d84a5d3b.png">


Resetting AX,BX register and Execution
<img width="710" alt="image" src="https://user-images.githubusercontent.com/59290560/193327468-766fa4fa-8c56-4bf7-84a3-72307814d2eb.png">


Flags:
<img width="81" alt="image" src="https://user-images.githubusercontent.com/59290560/193327506-aba0d222-bf76-4890-ba17-5dd2a15dd448.png">


Division alp
name "DIVISION"
org 700h
MOV AX,9H;
MOV BX,3H;
DIV BX;
MOV CX,AX;
MOV AX,0H;
MOV BX,0h;
HLT;


Output
AX and BX registers for DIVISION
<img width="716" alt="image" src="https://user-images.githubusercontent.com/59290560/193327562-f84c1fb9-5a6f-4714-b9b8-316975de2ca1.png">


Performing 8 Bit DIVISION
<img width="707" alt="image" src="https://user-images.githubusercontent.com/59290560/193327610-63e3cfab-8ae0-491e-a311-d0a5d46aab2d.png">


Moving to CX register
<img width="703" alt="image" src="https://user-images.githubusercontent.com/59290560/193327658-4cb38986-47cb-40e1-83b6-f34e8752a0d2.png">


Resetting AX,BX register and Execution
<img width="709" alt="image" src="https://user-images.githubusercontent.com/59290560/193327699-16d27f09-bd1f-4a5d-89bf-7ad38432dff1.png">


Flags:
<img width="98" alt="image" src="https://user-images.githubusercontent.com/59290560/193327740-96f7387d-1c04-4b40-af74-20beb927bdae.png">


Result :
Thus a program on ALP for the fundamental arithmetic and logical operations is done successful.
