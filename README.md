# microcontrollerProjects

  In the first project, characters are displayed on an LED pendulum in response to user input from a 
PC via UART. The text string on the pendulum is dynamically updated by the microcontroller, and 
a button may switch the display format between red-on-black and black-on-red by using UART and GPIO interrupts.

  In the second project, a button and an analog XY joystick are used to regulate an LED's brightness. 
Brightness can be adjusted by moving the joystick to the right, left, or center, which maintains
the previous brightness setting. By pressing the button, the dimmer function is maintained while 
the brightness can be switched between full and minimal.

  The third project applies the "Weighted Conversion Method" to transform an external analog voltage 
into a digital value utilizing an external DAC and TM4C1294 circuit board. On a BCD display, 
the four-digit digital value is then shown.

Overall, these projects show how to build several capabilities on the TM4C1294 microcontroller board 
using C programming, inbuilt ADC, PWM, UART, and GPIO interrupts.
