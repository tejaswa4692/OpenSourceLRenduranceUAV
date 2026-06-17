# Long Range Endurance UAV

This is a long-endurance autonomous fixed-wing UAV designed for lightweight package delivery and remote logistics missions.

The project focuses on creating a low-cost, energy-efficient and open source aircraft capable of autonomous waypoint navigation, payload deployment, and extended flight durations using commercially available components and a custom-built airframe.

## Design Preview

### Airframe Concept

![Screenshot 1](./assets/Screenshot2.png)

### CFD simulations at 50kmph

![Screenshot 2](./assets/Screenshot1.png)

## Key Features

* Autonomous flight using ArduPilot
* Pixhawk-based navigation and control
* Long-endurance Li-ion power system
* Lightweight foam-composite airframe
* Twin-motor propulsion system
* Payload delivery mechanism
* Modular and repairable design

## Hardware

### Flight Control

* Pixhawk 2.4.8
* uBlox Neo M8N GPS + Compass

### Propulsion

* 2× A2212 1000KV Brushless Motors
* 2× 30A ESCs
* 10×4.5 Propellers

### Power System

* 4S4P (or more) 18650 Li-ion Battery Pack

## Status

Currently the deisgn is being worked upon by me, the build process for it will be out soon aswell along with the respective 3d printable templates, im also testing different airfoils by cutting them out of thermocol and looking at their characterstics at different speeds while sitting in a car and them out the window.

Ive made the BOM for this which is linked in the repo, the total budget just comes under $180 with some wiggle room which was my initial goal and im quiet happy by what im gonna be able to do with this money, on the day i made the BOM price of 1 dollar was 94.49 rupees.

## Wing build process

1. print the 3d printed templates in the CAD folder
2. put them over a piece of cardboard and cut them out
3. Use CA glue to reinforce the cardboard and stiffen it up
4. take a 18x45x3cm piece of thermocol and on the 18cm side place the 2 templates you just cut out with nails or pins
5. wrap nichrome wire around 2 nails with approx 50cm distance between them attach the power wires on nails and power it using a powersupply (i used my old laptops 19V 2.5A supply)
6. slowly cut out the 45cm wing section out of the thermocol, dont worry if u dont nail it first try
7. Repeat this 4 more times to get total wing length of 225cm
8. join all the wing pieces together as shown in the assembly
9. use the 2m furniture stick to use as a wingspar, hotglue it under the wing where the cavity for it is, make sure it fits flush with the wing, if it doesnt, edit the wing template to fit your spar, the step files for the wing templates have been provided
10. Now cut your paper bag in approx 22.5cm sections
11. Cover a part of your wing with the mixture of craft glue + water and then place your piece of paper over it, make sure there are no airbubbles under the wing, do this for all around the wing
12. cut strips of 5cm and place it on the seams of the paper you laid down before
13. wait for your wing to completely dry before moving on
14. cut out alerons from both sides and make them 60 x 5 cm from both sides, dont cut the alerons completely, leave some paper at top part where it can flex
15. cut a 50 degree chunk out of the aleron so it can go up and down
16. cut out a slot for your servo and place it in with hotglue(remember to center it beforehand)
17. twist the stainless steel wire to create a pushrod and attach the 3d printed control horn on the aleron
18. put the pushrod wire through the assembly
19. cut a slit for the wire out and bring both wires to the middle (use jumper wires to extend the length of servo wires)
20. Put transpaarent packaging tape over your entire wing to smooth it out to reduce friction drag (optional)

Your wing is done it should look something like this 
![Screenshot 3](./assets/image.jpeg)
