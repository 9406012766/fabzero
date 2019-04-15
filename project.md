## Automatic Room Lighting System

Objective of the project:

1. The objective of this project is to make an Automated Room Lighting System which can automatically turn ON the lights by detecting the presence of human and turn OFF the light when no human presence is detected.

2. This project is useful since it aims towards conservation of energy which is most important.

3. The product would be useful in the those areas which require lights only when it is in use for eg: Staircase area, washrooms etc.

Components used in the project:

Micro-controller- At tiny-45 10 SU- 1no.

ISP Header – 1 no.

PIR Sensor – 1 no.

100 ohm resistor- 1 no.

10 K resistor- 1no.

LED- 1 no.

1 x 3 male Connector- 1no.

Solid State Relay- 1no.


## Working on the project:

![Schematic Diagram](img/schematic.jpeg "Schematic Diagram")

We prepared the schematic diagram of the circuit as per the pin connection of AT tiny-45 10SU data sheet along with above listed components through the KiCad.

![PCB Print in KiCad](img/pcbkicad.jpeg "PCB Print in KiCad")

The above schematic diagram was converted to PCB print to design the pin connection through KiCad and connected the pins of the components as the schematic diagram.

Then we made the Trace and Cut file of the above PCB design in ".camm" format.

Now we placed the an one side PCB in the "MonoFab" CNC machine and set the 64mm drilling bit to cut the Trace file which is as per the circuit diagram.

After cutting the trace file, we again set the another 32mm drilling bit to cut the Cut file which cut the outer portion of the main circuit board.