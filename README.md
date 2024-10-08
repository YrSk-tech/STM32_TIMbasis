# STM32 TIM Basic - Timer Period Elapsed Interruption Application

This project shows how to use a basic timer (TIM3) in an STM32 microcontroller to trigger period elapsed interrupts.

- **LED D2**: The timer toggles LED D2 every second.
- **Button Control**: Press button BTN_K0 to stop the timer interrupt.
- **LED D3**: A blink pattern for LED D3 is implemented in the Timer 3 callback function as a visual indicator controlled by the timer.
- **After 15 seconds**: After 15 seconds of running in the main loop, the `HAL_TIM_PeriodElapsedCallback` function starts, adjusting the timer and controlling the LED D3 blink pattern.

## TIM3 Configuration 
![image](https://github.com/user-attachments/assets/d257d5e5-e1c2-4866-a7de-805c9062387e)

## Clock Configuration 
![image](https://github.com/user-attachments/assets/5ceecb1a-d390-43bf-b39b-10a4a7007610)

Microcontroller STM32F4VE

Course name: Mastering STM32 microcontrollers

Link: https://www.udemy.com/course/mastering-stm32f407-microcontrollers/
