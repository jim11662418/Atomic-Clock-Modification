# Atomic-Clock-Modification
A simple modification to an atomic clock provides a visual indication the the WWVB signal is being received


https://github.com/user-attachments/assets/3c32a265-0068-47c1-9179-da709304ece9
<p align="center">The red LED in the lower right corner of the clock blinks once per second when the signal from WWVB in Ft. Collins, CO is received.</p><br>
<p align="center"><img src="/images/Atomic Clock Modification.png"/>
<p align="left">
In the schematic above, the modification uses one of the transistors in a CD4007 CMOS Transistor Array as an LED driver to light the LED when the WWVB receiver board in the clock receives a signal from Ft. Collins Co.

<p align="center"><img src="/images/Clock Internals.JPG"/>
<p align="left">
In the photo above, the WWVB receiver board inside the atomic clock can be seen in the lower left corner. The CD4007 is mounted "dead bug" fashion with hot melt glue in the lower right corner. On the received board, the wire connecting the 'PON' terminal to the clock board is removed. The 'PON' terminal on the receiver board is then jumpered to ground so the the receiver board is 'ON' at all times.


