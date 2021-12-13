# MSP430-device---Assembly-code
Using Assembly to interface with MSP430 microcontroller. for any project with 'root' file attached - contain the function for the routine.

1. GPIO (General Purpose Input Output) Led, Switch, Push-Button - change the input signal Dutycycle according to the switches position. show on LEDs.

2. Modes Operating, Interrupts - I write a code that expands the Hardware interrupt mechanism and supports prioritization of interrupt according to
   priority level, even when not happening together. This means, in the case of the arrival of a interrupt at a higher priority level, 
   the CPU will handle the high priority interrupt And then will return to treat the low priority level. 
   
3. Advanced and Basic Timer's and LCD - I execute command by pressing the buttons PB 0/1/2/3.
   (a) By pressing the PB0 button:
       It is required to perform a count from the value 0x00 and higher on an LCD screen (without displaying the counting history),
       With a delay of sec 1.
   (b) By pressing the PB1 button:
       output PWM signal at 1kHz with DutyCycle value starting from 0% and increasing all
       5sec at 20% cyclically.
   (c) I implement a counter (frequency counter) for measuring the frequency of an external clock signal fed from the signal generator to the controller foot.
       The measured frequency value displayed on an LCD screen, according to the following details:
       - Display the frequency in units of Hz.
       - On the screen appears frequency accuracy distance in Integers.

