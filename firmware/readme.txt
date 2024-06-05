

The files in the ERCxxxx folders are the firmware for the ARuniMK2 /ERsky9x based controller configured for use in a JR9303 
box. The main files named "ersky9x_jr_rom.bin" contain both the bootloader and the operating system and can be loaded on 
a blank board with the ATMEL built in bootloder and the SAMBA pc application. See the PDF discussing how to boostrap 
an erased chip. 

The bootloader_flas8.bin and the ersky9x_jr_rom.bin can also be flashed from the SD card individually once the system has 
booted and can display on the LCD. 

The source from which these binaries are created from can be found at github.com/garyStofer/mbtx 

The above .bin files might not be the very latest version, but a good starting point nevertheless.