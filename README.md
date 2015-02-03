Pi-OS
======


### Simple Raspberry Pi Operating System.


Following the tutorials [here](http://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/os/index.html) this is a very simple Raspberry Pi operating system written in ARMv6 Assembly language.

To use this OS, you will need to compile the code using the Yagarto GNU toolchain and simply replace the kernel.img file found on your Raspberry Pi SD card with the new kernel.img file generated by the compiler.

Credit goes to Alex Chadwick for the tutorials and the template code.

**Current status:** Allows keyboard input to be drawn to the screen.


I have left some of the older 'main.s' files in the repo so you can try them out:

	* Morse LED main.s - Flashes an LED in the sequence of the morse code
	* Random Lines main.s - Draws funky coloured lines to the screen in random places
	* cmdline Tag main.s - Draws out the content of the 'cmdline' Linux boot tag to the screen
	* Conversion Chart main.s - Draws a conversion chart for converting decimal to hex, to octal to binary.

