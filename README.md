UART dual board RX-TX.

TX(master): NVIC settings-gloabal interrupt enabled. DMA settings activated in usart2.

RecivetoIdle RX(slave): NVIC settings-gloabal interrupt enabled. DMA settings activated in usart2. RX pin is pull-down.

timer settings for master, TIM3 activated, clock source is internal clock, TIM3 gloabal interrupt enabled, prescaler:8400-1, Counter Period: 10000-1
gpio settings for master, PA0 is user button setted GPIO_EXTI0, GPIO mode is External interrupt mode with rising/falling edge trigger detection, GPIO pull-down
NVIC settings for master, EXTI line0 interrupt is enabled

https://wiki.st.com/stm32mcu/wiki/Getting_started_with_UART#Generate_source_code
