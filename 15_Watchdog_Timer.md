# Watchdog Timer

A Watchdog Timer (WDT) is an electronic or software timer that used to detect and recover from computer malfunctions.
Microcontrollers often include an integrated, on-chip WDT.
WDT monitors MCU programs to see if they are out of control or have stopped operating and resets the MCU if any occur.
WDT is based on a counter that counts down from some initial value to zero.
The embedded software select the initial value and must periodically restarts it. If the counter ever reaches zero, the software is presumed to be malfunctioning and WDT resets the MCU.
