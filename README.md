READ P2 REPORT FOR INSTRUCTIONS


• How to use your assembler program:
We have assembler.py, a python program that assembles our newly created assembly
language. We put this program in the same folder as a .txt file, this .txt file contains our
assembly program(written in our new language). Then we run the assembler.py
program. This program outputs a .txt file containing the hexadecimal encodings. In order
to load the image file into the cpu, we right click on the Instruction Memory and click load
image.

• Our cpu has 8 general purpose registers (r0, r1, r2, r3, r4, r5, r6, r7). Each register is 8
bits, so we can hold numbers up to 255. Our cpu can add and subtract, load memory
into registers and store register data into memory.

• Assembly Language Instructions that we created:
<dest> add <arg1> <arg2>
<dest> sub <arg1> <arg2>
<dest> load <adr>
<dest> store <adr>

