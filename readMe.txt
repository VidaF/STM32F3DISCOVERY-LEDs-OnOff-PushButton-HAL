/* Introduction */

Turn on and off the LED lights based on push-button

- HAL function has been used in order to control the LEDs and reading the push-botton status. 

/* Hardware */

STM32303 VCT6
STM32F3 Discovery board

/*Toolcahin */
This program is developed and compiled by using STM32CubeIE v1.11.4

gcc -mcpu=cortex-m4 -std=gnu11 -g3 -DDEBUG -DUSE_HAL_DRIVER -DSTM32F303xC -c -I../Core/Inc -I../Drivers/STM32F3xx_HAL_Driver/Inc/Legacy -I../Drivers/STM32F3xx_HAL_Driver/Inc -I../Drivers/CMSIS/Device/ST/STM32F3xx/Include -I../Drivers/CMSIS/Include -O0 -ffunction-sections -fdata-sections -Wall -fstack-usage -fcyclomatic-complexity --specs=nano.specs -mfpu=fpv4-sp-d16 -mfloat-abi=hard -mthumb


