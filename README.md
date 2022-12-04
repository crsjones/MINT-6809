# ASM80 Getchar, Putchar for 6502,6800 and 6809

The Z80 version of MINT was written using ASM80, the program sits on the usual
serial port routines Getchar and Putchar which allow it to be run on various hardware platforms.

Since ASM80 can assemble and emulate other processors including the above targets
a simple Getchar and Putchar is required.

The folders here have the same code for each processor, a continuous stream of a's and an echo, 
type a character to see it appear on the display terminal. 

### Howto

Copy the appropriate link to the Github repository;

https://github.com/crsjones/MINT-6809

https://github.com/crsjones/MINT-6502

https://github.com/crsjones/MINT-6800     ( Not working yet!)

Open an instance of ASM80 and paste the link into the text box that opens
when you press 'Import repo from Github'. 

Select the 'emulate.xxx' file and click 'compile [F9]' on the right menu.
If compilation is 'successfull' dismiss the successful box and click on 'Emulator [F10]'.
You should be rewarded with a procession of a's, click 'Back to IDE' in the top right corner to 
return to the code view.
uncomment the 'jmp echo' in the code to test the ACIA in loopback. 

