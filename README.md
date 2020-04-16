# Levinson 2u 40% Custom Default

This is a custom default layout for the Levinson 2u 40% split ortholinear keyboard by Keebio from keeb.io

## Flashing your Keyboard; Assuming you use Windows

When flashing a new keymap for any ATmega32u4 microcontroller setup use the following commands:

**Use MSys2 Bash**

    Open MSYS2 MingGW 64-bit

    Navigate to your qmk_firmware folder on MSYS2, for me, it is "cd /c/git/qmk_firmware"

    Put your keyboard in boot mode by pressing the RESET button, next to the microUSB plug on the LEFT keyboard. This is the master side.

    Type command: make keebio/levinson/rev2:keymapenamehere:avrdude
    
    *Replace keymapnamehere with your desired keymap.*
    
Follow the guide on https://docs.keeb.io/iris-rev2-build-guide/

