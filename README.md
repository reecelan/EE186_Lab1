# EE186_Lab1

Pt2.

During flashing LD4 blinks red and green and the program is built and uploaded via the STLink. During this process three files are created in a new debug folder: a .launch file, a FLASH.Id and a RAM.ID file.

The program goes into the MCU's internal flash, starting at address 0x0800 0000. 

The board has its own debugger built in, the ST-LINK/V2-1. It's a separate mcu (an STM32F103CBT6) and acts as a bridge to the target MCU's debug port.

The ST-LINK GDB server running the on-board ST-LINK. The protocol is SWD (Serial Wire Debug).
