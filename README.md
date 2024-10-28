# Atomic-Clock-Modification
This is a simple modification to an digital atomic clock that provides a visual indication that the signal from WWVB from Ft. Collin CO is being received. 

https://github.com/user-attachments/assets/3c32a265-0068-47c1-9179-da709304ece9

<p align="center">The red LED in the lower right corner of the clock blinks once per second when the WWVB signal is received.</p><br>
<p align="center"><img src="/images/Atomic Clock Modification.png"/>
<p align="left">
In the schematic above, the modification uses one of the transistors in a CD4007 CMOS Transistor Array as an driver to light the LED when the receiver module in the clock receives a signal from WWVB.

<p align="center"><img src="/images/Clock Internals.JPG"/>
<p align="left">
In the photo above, the WWVB receiver module inside the atomic clock can be seen in the lower left corner. The CD4007 is mounted "dead bug" fashion with hot melt glue in the lower right corner. On the receiver module, the wire connecting the 'PON' terminal to the clock board is removed. The 'PON' terminal on the receiver module is then jumpered to ground so the the receiver is 'ON' at all times. This will, unfortunately, reduce battery life somewhat. This particular clock is an 'Atomix' brand, but most atomic clocks should be very similar inside. Note that the terminals on your receiver module may be labeled differently.


