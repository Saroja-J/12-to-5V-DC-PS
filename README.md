## 12-to-5V-DC-PS 
### Overview
   This circuit converts an unregulated 12V DC input into a regulated 5V DC output using a 7805 linear voltage regulator. The 7805 is a 3 terminal IC that maintains a constant 5V output even if input voltage or load current varies. I/P capacitor C1 noise/ripples from the 12V source while output capacitor C2 stabilizes the 5V and improves transient response. LED acts as a power indicator. This design is simple,cheap and reliable for low-current 5V circuits.
### Working
Input - 12V dc enters through input terminal and capacitor C1 filters the noise/ripples.
Regulation - 7805 drops excess voltage as heat and provide 5V at output.
Output - C2 removes high frequency noise and provide stable %V at output.
### Hardware specification
Barrel_Jack - I/P connector for 12V input
C1 capacitor(100uf/25V) - I/P filter
U1 L7805 - Linear regulator, provides 5V/1A at output terminal
C2 capacitor(10uf/16v) - O/P filter
R1 resistror(460 ohms) - current limiting resistor for LED
LED1 - Power Indicator
J2 connector - Output terminal
### Features
* Fixed 5V Regulated Output from 7V-35V input.
* Overload protection
* simple 3 pin interface
### Applications
-Microcontroller board, sensor module,Logic circuits likewise where there is a requirement of 5V stable Dc voltage. 
### NOTE
* Minimum 7V needs to be provided at the input to get stable 5V at output
* For 200mA< load current require proper HeatSink.
