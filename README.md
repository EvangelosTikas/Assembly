# Main coding samples for a variety of programmas
Used mainly for the 8051 Microcontroller
#Why Assembly Language?
Although High-level languages are easy to work with, the following reasons point out the advantage of Assembly Language

The Programs written in Assembly gets executed faster and they occupy less memory.
With the help of Assembly Language, you can directly exploit all the features of a Microcontroller.
Using Assembly Language, you can have direct and accurate control of all the Microcontroller’s resources like I/O Ports, RAM, SFRs, etc.
Compared to High-level Languages, Assembly Language has less rules and restrictions.

Examples


ORG 0000H               ; Tells the Assembler to assemble the next statement at 0000H

LJMP MAIN              ; Code Memory at 0000H. Jump to MAIN.

ORG 000BH               ; Tells the Assembler to assemble the next statement at 000BH

MAIN: NOP               ; Code Memory at 000BH. MAIN starts here.
