For a university subject, we were tasked with creating a small handheld device, very similar to a classic Nintendo Gameboy. This included both hardware design and writing the software to make it run. We were required to design a 2 sided PCB in Altium Designer, and then send our designs off for PCB manufacture in China. After a several week delay our boards came back and we could start hand assembly of the various components. After countless hours spent refining it in the design phase, it was very satisfying when my board came back and I assembled it and the hardware worked perfectly. We then had to program the microcontroller bare metal with C. There is no operating system involved. This involved writing code for a framebuffer in memory, and then implementing the protocol to communicate this framebuffer to the LCD, and instruct it to draw it on the screen. A stretch objective was to establish read and write control of an external SDRAM chip. I completed these successfully, and below is a picture of the system displaying a counting (in binary) pattern which is being read from the external RAM. 

I achieved full marks for this project, and even got a fun little game of snake II implemented!

![System on](img/work/gameboy/screenon.jpg)

An Altium Designer render of the "back" of the system

![System rear](img/work/gameboy/backrender.PNG)
