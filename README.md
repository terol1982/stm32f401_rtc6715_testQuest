# stm32f401_rtc6715_testQuest
test Quest to make library for rtc6715

Проект зроблен під stm32f401rbt з використанням stm32cubemx та stm32cubeide. В проекті використовується FreeRTOS. 
Вся логіка роботи знаходиться у файлі core/src/freertos.c. Бібліотека в файлах core/src/rtc6715.c та core/inc/rtc6715.h.
SPI зроблен програмно.

3 кнопки для задання частот:
BTN1 (PB12) - freq1=5865G
BTN2 (PB13) - freq2=5733G
BTN3 (PB14) - req3=5705G
кнопки підключаються відносно землі

2 status LED:
RW LED (PB15)
RW ERROR LED (PC6)
