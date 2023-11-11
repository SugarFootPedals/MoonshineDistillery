# MoonshineDistillery
# WARNING: Uses 120v AC. Lethal Voltages. No Warranty Expressed or Implied. Use at your OWN RISK! NOT LIABLE FOR DAMAGES OR INJURIES INCURRED
# FOR EDUCATIONAL PURPOSES ONLY. Unauthorized Moonshine production is ILLEGAL.

This project is a result of watching the Discovery Channel television show "Moonshiners".

It uses an Arduino ProMini controller to detect the various stages of moonshine production and keeping a 120vAC Hot Plate at optimum Temperatures.
A "K-Type" sensor monitors the MASH temperature.
120vAC is fed into the circuit board and switched via a relay controlled by the ProMini for 120vAC for the HOT PLATE.

DS18B20 Temperature sensors monitor the VAPOR and THUMPER Temperatures and displays these reading via the OLED Display and LED's, which indicate FORESHOTS, HEADS, HEARTS and TAILS.

A SMPS circuit provides the voltages for the rest of the circuit board ( +12vDC and +5vDC ) .

Please view the multi-page SCHEMATIC for all info related to moonshine stages and implimentation of sensors.
CODE is written and compiles (worked in a simulation) , but is untested and UNVERIFIED with the circuit board.

A "cover faceplate" circuit board gerber is included.
