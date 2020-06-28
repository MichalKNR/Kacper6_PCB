# Kacper6_PCB
A STM32 based motor driver hat for Raspberry Pi4 with capability to power RPI4 at full trhottle, full battery monitoring, power led drivers, encoders inputs and servos output.

# Functionalities

* Control based on UART commands
** It is possible to use RPI4 or bluetooth connector as long as data provided from both sources will comply with requirements.
* Dual channel motor driver for 1A continous each and 3A peak
* Two 12W power LEDs output with programmable dimmer and lighting patterns
* Two encoders inputs for precise speed control
* Two programmable PWM outputs
** Those outputs can works either as servos output or WS2812 outputs.
