# Eco M3 Deep
It is my custom built 3D printer, with all custom 3D printed parts with large bed area.

I made this printer as it would help in making other projects as i don't have direct access to one, and i am interested more on hackclub events projects & science projects which constantly need custom 3D printed parts.

![The Printer](./Rendered/ThePrinter.png)

## Features 
    - Simplicity
    - Large Bed size with area of 40cmx40cm
    - Remote Extruder
    - The structure & large bed mount are made from wood to reduce cost
    - Expandable design for future additions

## Assembly
1. Mounts 

    - It is simple, start by putting linear bearings into the mounts specifically the moving z axis and the hotend mounts. 
2. Attachments
    -  Screw the hotend
    - Attach mechanical stops with the y axis motor, the same applies to the z axis bottom mount.
    - Screw the x axis bed motor onto its place.
    - Add the pulleys onto the motors shafts and onto a 3D printed small 8mm shaft that is connected to a 8mm bearing.
3. Structure
    - Make 7x 2x3cm wooden part with length of 50cm, put them together as in the image.
4. Axes assembly
    - Z axis
        - Connect the bottom z axis motor to the coupler and the coupler to the T8 lead screw.
        - Connect the T8 screw nut onto its place on the movable z axis middle mount.
        - Connect the upper z mount that has an 8mm bearing into the T8 screw.
        - Stabalize the structure by connecting the linear rod into its place through the three mounts.
        - The same applies on the other side
    - X axis
        - Mount the motors
        - Place the linear rods into their mounts 
        - Put the linear bearings into thier movable mounts.
        - Screw the movable mounts onto a 45x45cm wooden bed.
    - Y axis
        - Mount the hotend into its place
        - Connect the linear bearings
        - Screw the hotend mount onto the movable part.
5. Mechanism
    - Attach the timing belts to the mounts for z - x - y axes.
    - Connect all cables to the mainboard
6. Firmware
    - Install Marlin 2.0 firmware

## Bill of Materials (BOM)

| Name                     | Description                                                                 | Unit Price | Quantity | Total Price | Total in USD | Link                                                                                                 |
|--------------------------|-----------------------------------------------------------------------------|------------|----------|-------------|--------------|-----------------------------------------------------------------------------------------------------|
| Stepper Motors           | Nema 17 Stepper motor 17hs8401s Usongshine 48mm (Black)                    | 825        | 5        | 4125        | 81.65083135  | [Link](https://www.amazon.eg/-/en/gp/product/B0969CFKLM/ref=ox_sc_act_title_1?smid=A26I4OU0GDWZ7W&psc=1) |
| Linear Rods              | Stainless Steel Linear Rod (8mm, 1m)                                        | 260        | 3        | 780         | 15.43942993  | [Link](https://www.amazon.eg/-/en/gp/product/B09Z3QJF1P/ref=ox_sc_act_title_2?smid=A3G2ZVUBEERR0N&psc=1) |
| Pulleys                  | GT2 Timing Pulley 20 teeth Bore 5mm 2 Pcs                                  | 149        | 2        | 298         | 5.898653998  | [Link](https://www.amazon.eg/-/en/gp/product/B0969JNT3G/ref=ox_sc_act_title_2?smid=A26I4OU0GDWZ7W&psc=1) |
| Remote Extruder          | MK8 All-Metal Remote Extruder for 3D Printer Parts - 1.75mm                | 350        | 1        | 350         | 6.927949327  | [Link](https://www.amazon.eg/-/en/gp/product/B0968WV7D8/ref=ox_sc_act_title_4?smid=A26I4OU0GDWZ7W&psc=1) |
| End Stop                 | 3D Printer Mechanical End Stop Switch Module                               | 89.99      | 3        | 269.9       | 5.342438638  | [Link](https://www.amazon.eg/-/en/gp/product/B0968R6TJ8/ref=ox_sc_act_title_5?smid=A1G5VPUVPXBMQ6&psc=1) |
| Motors Couplers          | 3D Printer and Cnc Stepper Motor Flexible Coupling Coupler (5 to 8mm)      | 105        | 2        | 210         | 4.156769596  | [Link](https://www.amazon.eg/-/en/gp/product/B0968ZBB2J/ref=ox_sc_act_title_6?smid=A26I4OU0GDWZ7W&psc=1) |
| T8 Lead Screw            | T8 Thread Lead Screw 8mm, 2mm with Brass Nut (500mm)                      | 295        | 2        | 590         | 11.67854315  | [Link](https://www.amazon.eg/-/en/gp/product/B0969HF39S/ref=ox_sc_act_title_7?smid=A22MDF17B7GE04&psc=1) |
| Linear Bearings          | Linear Bearings 3D Printer, LM8UU, 8mm, 6 Pieces                          | 249        | 2        | 498         | 9.857482185  | [Link](https://www.amazon.eg/-/en/gp/product/B0968Y5C94/ref=ox_sc_act_title_8?smid=A3HOVOH12T9VII&psc=1) |
| Timing Belt              | adp GT2 Timing belt 2mm pitch 6mm wide Rubber Opening Timing Belt For 3D Printer - 2M | 275 | 1 | 275 | 5.443388757 | [Link](https://www.amazon.eg/-/en/gp/product/B099DC5JK5/ref=ox_sc_act_title_9?smid=A26I4OU0GDWZ7W&psc=1) |
| Hot End                  | CUHAWUDBA 3D Full Metal J-Head CR10 Hotend Extruder Kit Hot End Kit for CR10 10S Bowden Extruder 24V 40W 3D Printer Parts | 610 | 1 | 610 | 12.07442597 | [Link](https://www.amazon.eg/-/en/gp/product/B082WQVCKT/ref=ox_sc_act_title_10?smid=A3HOVOH12T9VII&psc=1) |
| Power Supply             | Power Supply 24V 10A.                                                      | 595        | 1        | 595         | 11.77751386  | [Link](https://www.amazon.eg/-/en/gp/product/B0DR633KMW/ref=ox_sc_act_title_11?smid=A2DMKAT7ZKLGQN&psc=1) |
| SKR 1.4                  | SKR V1.4 TURBO                                                             | 2,999.00   | 1        | 2,999.00    | 59.36262866  | [Link](https://www.amazon.eg/-/en/gp/product/B09BMGXJ8S/ref=ox_sc_act_title_12?smid=A3HOVOH12T9VII&psc=1) |
| Stepper Motors Drivers   | TMC2209 V2 Stepper Motor Driver                                            | 480        | 4        | 1920        | 38.00475059  | [Link](https://www.amazon.eg/-/en/gp/product/B0DJZL2XPQ/ref=ox_sc_act_title_15?smid=ANKKSL5YJGFAH&psc=1) |
| Heated Bed               | Aluminum Heated Bed for 3D Printer (400x200x3mm)                           | 500        | 2        | 1000        | 19.79414093  | [Link](https://www.amazon.eg/-/en/gp/product/B099D8ZBVM/ref=ox_sc_act_title_1?smid=A2TUHD4CZOFOST&psc=1) |
| Bed Leveling Screws      | 3D Printer Bed Leveling M3 Screw with Spring and Hand Knob 5 Pieces        | 155        | 2        | 310         | 6.12  | [Link](https://www.amazon.eg/-/en/gp/product/B0968XHW56/ref=ewc_pr_img_1?smid=A22MDF17B7GE04&psc=1) |
| Cooling Fan              | 3D 4010 Brushless Cooling Fan, 24v DC with Ball Bearing 2pin Connector     | 90         | 1        | 90          | 1.781472684  | [Link](https://www.amazon.eg/-/en/gp/product/B0DJ9R2ZJ3/ref=ewc_pr_img_1?smid=A2DMKAT7ZKLGQN&psc=1) |
| Thermistors              | 100K Ohm NTC 3950 Thermistors Temperature Sensor with Cable Dupont Head for Reprap Mendel MK2A MK2B Heated Bed 3D Printers Parts | 100 | 3 | 300 | 5.93824228 | [Link](https://www.amazon.eg/-/en/gp/product/B09MSPWTM5/ref=ewc_pr_img_1?smid=A26I4OU0GDWZ7W&psc=1) |
| 5mm Bearings             | uxcell 625-2RS Deep Groove Ball Bearing 5x16x5mm Double Sealed ABEC-3 Bearings 10-Pack | 216 | 1 | 216 | 4.275534442 | [Link](https://www.amazon.eg/-/en/gp/product/B07TML6YP4/ref=ox_sc_act_title_1?smid=A24L91U83A8RCR&psc=1) |
| Air blower               | DIY-Kit DC 12V Air blower,5cm Turbo blower,Humidifier fan,speed 4600RPM,3D Printer parts,cooling fan,Locking protection - 3D Printer 5015 Radial Turbo Blower 12Vdc Fan (SKU#1014) | 134.99 | 1 | 134.99 | 2.672011085 | [Link](https://www.amazon.eg/-/en/gp/product/B0D9TDTDCH/ref=ewc_pr_img_1?smid=A1G5VPUVPXBMQ6&psc=1) |

**Total**                                                                     |             |          | 15570.89 | 308.1962074 |

**Total In USD (According to the conversion rate at 18/6/2025)** ***309$***     