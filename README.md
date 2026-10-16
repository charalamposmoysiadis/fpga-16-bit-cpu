# fpga-16-bit-cpu
A 16 bit CPU designed in Lucid
Note: This project is to be run on the simulator of Alchitry Labs, that has the Vivado on backend. I do not have a board so it may not work there if you try

This is a 16 bit CPU, designed in Lucid, an hdl for the Alchitry Labs, which basicly works with Vivado as it is a Xilinx-AMD, technology.
In the instRom there is a simple but efficient bit counting file that shows that this simple cpu is running. 
This is NOT made by a professional but by a student and it may have issues. Currently i am investing in making it better, so there may be small changes in the future.
Throughout the project i have made comments in english and in greek. English ones are more formal while greek ones are more friendly as it was better for me to truly express myself in my mother language. If there is any misconception feel free to contact me.
In order to truly understand and make this project I had to make several other projects, like a led blinker, in order to understand sequential, combinational logic and their differences.

Credits: This project is based on the architecture and design concepts from the book: MISSION IMPOSSIBLE - BUILD YOUR OWN CPU FROM SCRATCH by Doug Domke
While the main core structure follows the book's suggestions, i have customized and added some features , such as many instructions that were not directly and fully explained in the book neither their cpu code(pushi, pushr, pulr, puli, in, out, jmp, jz, jnz, jne, jlt, rtn, add, sub, and, or ...) and some other changes.

