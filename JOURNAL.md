---
title: "Eco M3 Deep"
author: "Mohamed Samir"
description: "Describe your project in a short sentence!"
created_at: "2025-06-6"
---

Total time spent: 64h

## Day 1 (06/6) 
> Spent: 4h

I made a lot of research on how 3D printers work, in addition to their different types and what are the different components they share and advantages and disadvantages in components types.

## Day 2 (07/6)
> Spent: 5h

Continued watching more videos, i was interested in simple cartesian bed slingers, in which i searched about how they are assembled and different design strategies.

## Day 3 (08/6)
> Spent: 5h

Built ideas about the design and materials needed, i decided to a woooden frame & bed mount as they would otherwise raise the cost.
## Day 4 (09/6)
> Spent: 9h

Chose the bed size to be 40x40cm with total structural dimensions of 50cmx50cm.
For the electronics i chose it to be a simple single hotend with bowden extruder as i focus more on speed printing, with SKR 1.4 mainboard. 
## Day 5 (10/6)
> Spent: 8h

Started desiging the x axis mount, i had to go through various implementations and modifications 

- This is the first version of the design
![Bed Mount first](./Images/BedMount_V1.png)
After putting work on the first design i realised how non feasable it was. Which made me thinking about a much better abstraction. 
- Final Version
![Bed Mount](./Images/Bed%20Mount.png)

## Day 6 (11/6)
> Spent: 10h

I started working on the z axis.

This is the bottom mount for the dual z axis motors.

![](./Images/Bottom%20Mount%20Z%20axis.png)

The second part is the middle moving part that holds the y axis motor to the pulley and also has the screw mount that is used in moving up & down by the rotating T8 screw. I made a small 8mm shaft that would be inserted into the pulley and connected to the part on the left.

![](./Images/Middle%20Mount%20Z%20axis.png)

## Day 7 (12/6)
> Spent: 7h

Finalized the z axis mounts. The upper mount which has an 8mm bearing to stabalize the T8 screw with the screw holes on the top to be secured on the wooden structure. 

![](./Images/Upper%20Mount%20Z%20axis.png)

I also started searching for the materials on different shopping websites, at first i checked aliexpress but i found the linear rails they sell are expensive in addition to the shipping cost. I decided to search for the materials on amazon.eg which had all materials but some were different or out of stock, like the hotend which is the CR10 Bowden extruder kit. which i had to choose because the site didn't have any other 24v hotends.

## Day 8 (13/6)
> Spent: 13h

I designed the extruder mount with the hotend mount.

I decided to put the extruder on the top of the structure with screw holes on the bottom.

![](./Images/Remote%20Extruder%20Mount.png)

For the hotend mount i made 2 holes for mounting the CR10 hotend and additional holes for future modifications.

![](./Images/Hot%20End%20Mount.png)

 The backward side of the mount, has two square hollow structures that are used for holding the moving timing belt.

![](/Images/Hot%20End%20Mount%202.png)
## Day 9 (14/6)
> Spent: 3h

Started finalizing the printer and assembeld all parts on the software.
![](./Images/ThePrinter.png)

![](./Images/ThePrinter%202.png)