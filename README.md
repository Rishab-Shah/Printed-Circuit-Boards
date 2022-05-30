# Printed Circuit Boards and Labs
All Assignments and boards created as part of PCB - ECEN 5730

## Boards:  
#### Board 1: IC 555 circuit  
The Output of the 555 timer should drive 4 LEDs with different brightness and should have a duty cycle of 60 percent and 500 Hz. It was to understand the behavior of switching noise experienced at fast rise times.  

#### Board 2: Good Layout Vs Bad Layout  
There will be two designs integrated in one – Good Layout and Bad Layout for Hex-inverter driven by a 555 timer. The good layout would have a decoupling capacitor in proximity and a contiguous ground plane whereas a Bad layout would have decoupling capacitor placed far away as well only one via to the ground plane (no common ground place).  

#### Board 3: Golden Arduino:  
The Golden arduino should be able to boot after burning the bootloader should be able to execute a test blinky program and have lower switching and ground bounce noise compared to the commercial arduino board.

#### Board 4:  Golden Arduino Shield:  
A 4-layer board with following sensors is to be made along with the care for each sensor if applicable is mentioned
• A temperature-humidity sensor -- GPIO line </br>• A Hall effect magnetic field sensor – Connected to ADC </br>• A CO, carbon monoxide sensor (MQ-7) </br>• A microphone A3 of arduino </br>• At least 4 smart or digital LEDs – GPIO line with a 1K ohm resistor in series </br>• A buzzer – GPIO line with PWM </br>• A 16 bit ADC – ADDRR grounded for address selection </br>• A 12 bit DAC - D0 of Arduino Uno </br>•A heartbeat sensor – LED’s are on the opposite side and are bright and Red in color – 47 Ohm resistor, Connected to ADC   

16-bit ADC to measure the heartbeat sensor and the CO sensor as single ended voltages and the Hall effect sensor as a differential signal. The schematics for each of the sensor is referred from the digikey as well as lecture notes.SCl ,SDA should have a 10K pull-up.Man care is that the headers should be aligned with the arduino uno as well as the shield should not cover the board completely otherwise there will be an access issue to the board.

## Labs:
Labs covered topics to understand following signal integrity characteristics:  
1. Understanding the breaking point of each trace width based upon current capacity  
2. Methods to reduce Ground bounce  
3. Importance of Comon continuous ground plane  
4. ESD protection of devices  
5. Methods to reduce EMI  
6. Importance of differential measurement for eliminating noise  
7. Importance of Quiet high and Quiet Low in switching noise measurement  
8. Importance of a debounce circuit  
9. Designing of a Oscillator circuit and methods to introduce stability by buffered output
