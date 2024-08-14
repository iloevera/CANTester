# CANTester
Connection tester for 4P4C and 8P8C cables and CAN bus terminator resistance tester

## Connection Tester
Tester for 4P4C and 8P8C cables. Turns on LEDs on the transmit side in sequence and sends the signal through the connected cable. If the cable is connected properly, all the LEDs on the receiver should turn on in the same order. 
### Instructions
1. Pick the number of pins in your header (4P4C, 8P8C). An LED will indicate your choice.
2. Plug both sides of your cable (Transmit & Receive)
3. The lights marked 1-8 on both sides of the bottom box should turn on in order. If not, your cable is broken.

## Terminator Resistance Tester
Tester for CAN Terminators. LED turns on if the resistance between CANH and CANL (Pins 2 and 3) is 120R. 
### Instructions
1. Plug in your CAN terminator (4P4C with a 120R in the middle two pins).
2. LED in the box will turn on if middle two pins are 120R.
