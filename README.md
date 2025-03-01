# cubemx_f429zit6_cmake
generate stm32f429zit6 project in cmake version using stm32cubemx, with GPIO pb1 set high level, you can just compile this project in your windows or linux terminal.

It needs to be emphasized that the executable file is in elf form, if you want to download to stm32f429zit6 board and make it run, you have to transfer it into hex form, with following command "objcopy -Oihex file.elf file.hex"
