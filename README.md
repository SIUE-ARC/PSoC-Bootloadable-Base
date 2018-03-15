# PSoC-Bootloadable-Base
A base project for working with the PSoC4 CY8CKIT-049 development boards with onboard UART bootloader.

The CY8CKIT-049 does not use a standard KitProg USB programmer. It instead has a USB->UART converter IC and comes shipped with a UART bootloader programmed onto the microcontroller. This project provides a base for working with this bootloader. Changes can be made to **Bootloadable Blinking LED** PSoC creator project. Once a project is ready for upload this can be done by using the Bootloader Host utility program under the tools menu in PSoC Creator.
