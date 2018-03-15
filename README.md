# PSoC-Bootloadable-Base
A base project for working with the PSoC4 CY8CKIT-049 development boards with onboard UART bootloader.

The CY8CKIT-049 does not use a standard KitProg USB programmer. It instead has a USB->UART converter IC and comes shipped with a UART bootloader programmed onto the microcontroller. This project provides a base for working with this bootloader. Changes can be made to **Bootloadable Blinking LED** PSoC creator project. Once a project is ready for upload this can be done by using the Bootloader Host utility program under the tools menu in PSoC Creator.

# Using the Bootloader Host
From to tools menu launch **Bootloader Host**. Select the bootloadable program file (.CYACD) from **project_root/CortexM0/ARM_GCC_541/Debug**. Plug in the CY8CKIT-049 development board into the USB port. Press and hold the push button on the board for 1 second and release. If the LED is pulsing then the bootloader is active and the device can be programmed. Select the appropriate COM port from the ports list. Use baud rate of 115200, 1 stop, no parity. Click program. The Bootloader Host tool will report if it was successful or if there were any errors.
