⚠️ **WARNING: THIS PROJECT INVOLVES HIGH VOLTAGE (120V AC), RECREATE AT YOUR OWN RISK!** ⚠️

# Simple Power Supply

This is a simple ±12V 1A bipolar linear power supply using the LM317 and LM337 linear voltage regulators. This is an ideal low noise power supply for sensitive analog circuits such as op-amps and audio amplifiers. The circuit schematic can be found [here](https://github.com/GREENSHELLRAGE/simple-power-supply/blob/main/Power%20Supply%20Schematic.pdf).

![Front of power supply](https://raw.githubusercontent.com/GREENSHELLRAGE/simple-power-supply/main/images/IMG_4641.png)
![Back of power supply](https://raw.githubusercontent.com/GREENSHELLRAGE/simple-power-supply/main/images/IMG_4642.png)
![Inside of power supply](https://raw.githubusercontent.com/GREENSHELLRAGE/simple-power-supply/main/images/IMG_4644.png)

# Notes for assembling the circuit

- Mount the LM317 and LM337 regulators on heatsinks (they will get warm)
- The metal case of the supply is connected to earth, the GND connector on the front is isolated from earth
- Cover all exposed 120V connections with electrical tape to prevent accidental shocks/shorts
- ⚠️ **DO NOT TURN ON THE CIRCUIT UNTIL ALL CONNECTIONS HAVE BEEN MADE FIRMLY** ⚠️
- ⚠️ **ONLY USE ONE HAND TO MAKE ADJUSTMENTS TO THE CIRCUIT WHILE IT IS POWERED ON** ⚠️

To set the output voltages, connect a multimeter between the GND and +12V outputs. Turn on the power supply and use a screwdriver to adjust the potentiometer connected to the LM317 until the multimeter reads 12V. Do the same for the -12V output and the potentiometer connected to the LM337.
