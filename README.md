# Traffic Light Using CD4017 and NE555

1. Description
A simple traffic light circuit using NE555 timer and CD4017 counter ICs. It controls Red, Yellow and Green LEDs
in sequence.

2. Components
- NE555 Timer IC
- CD4017 IC
- Red, Yellow & Green LEDs
- Resistors & Capacitors
- Diodes
- Perfboard

3. Working
NE555 generates clock pulses for the CD4017. The CD4017
controls the LEDs sequentially.

- Red LED   : 2 diodes for timing delay
- Yellow LED: 1 diode for timing delay
- Green LED : 2 diodes for timing delay

Sequence: Red → Yellow → Green