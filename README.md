# TM4C123GH6PM_UART0_Serial_Monitor

_**>>>This project and its source codes are available for educational purposes and not for commercial uses unless agreed/permitted. The distribution of this software after modifications on educational grounds must be mentioned explicitly. Anyone using or distributing this project completely or partially for commercial use can and will be subjected to proper legal actions according to international or regional laws, rules and regulations<<<**_

This is C program of serial monitor at baud rate of 115200 bits/sec for real time observing the values of variables and registers on Computer screen with which TM4C1233H6PM Launchpad is connected. UART0 is one of the serial communication protocol available on TM4C123. The file included in this repository is C header file (.h). Whoever wants to use this header file must import it with his/her project files and initialize the UART module with following function:

UART_Init();

Printing format is as follows:

For integers:
UART_printf_int(int integer_number);

For float/double:
UART_printf_float(float some_float_number);

For char:
UART_OutChar(char some_char);

For character string:
UART_printf(some_char_array);
