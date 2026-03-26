# STM32_Nucleo_Encoder_NVIC
Code for STM32F446RET6 to get encoder counts using Timer Interrupts

This project demonstrates how to read quadrature encoder counts using the STM32F446RET6 microcontroller with a combination of:

1. Timer Encoder Mode (for hardware decoding)
2. Timer Interrupts (for periodic sampling/processing)

Instead of continuously polling the encoder value, this approach uses interrupts to efficiently read and process encoder data at fixed intervals.

Features

1. Hardware-based quadrature decoding (TIM Encoder Mode)
2. Periodic reading using Timer Interrupts
3. Reduced CPU usage (no busy polling)
4. Suitable for real-time motor control
5. Easily extendable for speed (RPM) calculation
