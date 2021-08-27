# NUCEO_F722ZE_MBEDOS
Files modification to include support to Nucleo-F722ZE board in MbedOS

The nucleo-f722ze board don't have mbed support\
This files are modifications to include this support

How to use?
 - Drop the mbed-os folder to your program path.
 - The compiled bin program can be loaded to the board with the st-link program or drag and drop to the node device, using the run program in Mbed-IDE will have a pyocd error but the program will be loaded to flash with success

Issues:
 - Every new program in Mbed-IDE need this modifications.
 - Delete your target or copy the folder to the path target too.
 - Load and debugger is not avaliable in mbed-tools or mbed-IDE, working around this.
 - When using drag and drop in board the stlink can't access the chip in software reset option, the hardware reset option must be selected
