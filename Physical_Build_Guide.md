# BabyBelt Pro V2 Pysical Build Guide
BabyBelt Pro V2 by RobMink

Firmware guides by TheyCallMeZ aka BlueWyvern

Physical Build Guide by Brent Lieb and Dr. Mason McNair of the Plants X Tech Lab at Michigan State University

## Introduction
Hello! This is the build guide for the BabyBelt Pro V2 by RobMink. This guide was written with new builders in mind, so don't be intimidated if this is your first printer! The guide includes images when possible and assumes the user is building from the {Fabreeko build kit w/ link?}. 

How to read this guide:
 - *Printed Parts* will be in italics
 - **Kit Parts** will be bolded
 - Printed Parts will link to the specific file in the github if clicked on
 - Printed part name prefixes include
   - [a] = accent color
   - [s] = needs supports
   - [HT] = should be printed in a strong heat tolerant material (PETG, ABS, ASA, PA) to avoid premature wearing

>[!TIP] 
>If you are not familiar with 3D Printers and their components, it is recommended that you leave the parts from the kit in their packaging until the guide instructs you to unpack them. This will help you keep track of them and avoid confusion later. 
## Tools Needed 
- 2.5mm Hexagonal Screwdriver
- 2mm Hexagonal Screwdriver
- 1.5mm Hexagonal Screwdriver
- Adjustable Wrench
- Wire Cutters
- Small Flathead Screwdriver
- Files (Good to have on hand if any parts print with slight imperfections)
- Scissors & Iron (For print belt)

## Printed Parts
### Printing Parts
Most of the parts of this kit can be printed out of normal PLA, allowing for a wide range of colors and stylistic choices! The parts that shouldn't be printed out of PLA are listed below. 

- [*Nema17_ZGear*](Printed%20Parts/ZBeltDrive/[HT]_BBProV25fl_Nema17_ZGear.stl)
- [*Roller_ZGear*](Printed%20Parts/ZBeltDrive/[HT]_BBProV25fl_Roller_ZGear.stl)
- [*UnderbedOrBed*](Printed%20Parts/ZBeltDrive/[HT]_BBProV25fl_UnderbedOrBed.stl)

We recommend printing all parts with standard Voron style settings:

- Layer height: 0.2mm
- Extrusion width: 0.4mm, forced
- Infill percentage: 40%
- Infill type: grid, gyroid, honeycomb, triangle, or cubic
- Wall count: 4
- Solid top/bottom layers: 5

The design inspiration for the printer built for this guide was to make a printer out of "wood", "stone", and "glass" which is why we selected [Timberfill](https://fillamentum.com/collections/timberfill-filament/) as the primary filament, [Marble PLA](https://us.polymaker.com/products/panchroma-marble?variant=43612877946937) for the accent color, and [Fiberon PA6-GF](https://us.polymaker.com/products/fiberon-pa6-gf25) for the heat tolerant components. 

### Part List

Coming Soon!

>[!NOTE]
>If you are using a Revo-style Hot End and not the Bamboo nozzle that comes with the Fabreeko kit, then the gantry-carriage parts will be slightly different and can be found in the "Mods" folder. 
## Kit Parts
This is what the box will look like when you receive it.  

<img src="Images/1" width="600"/> 

This is all of the parts that will be inside the box, spread out for visibility.  

![Baby Belt Kit Parts](https://github.com/user-attachments/assets/4962c9a2-cb96-40d1-8257-9bf0a76a4f9a)


### Part List

Coming Soon! In the meantime [see the BOM here](https://docs.google.com/spreadsheets/d/19PbR3nFbQ4-eIOTU0kmoTl5-mHv_KsTnUdfFXekWg-I/edit?gid=0#gid=0)

## Physical Build
>[!NOTE]
>There are several times during this build when a component will be secured with multiple screws. It is generally recommended to NOT fully tighten a screw before the rest have been started, to make sure parts line up correctly and don't crack. 
### Base
> I mean I prefer treble but okay

Start by constructing the base. 
- Place an **M3 Nut** into the hole indicated by the arrow in [*Side-B*](Printed%20Parts/Frame/BBProV25fl_Side-B.stl)
<img src="Images/3" width="600"/>

- Join the two sides together and place one **M3x20 screw** into the indicated hole in [*Side-A*](Printed%20Parts/Frame/BBProV25fl_Side-A.stl) and tighten. 
<img src="Images/4" width="600"/>

The base should now look like this.

<img src="Images/5" width="600"/>

### Power Switch and Jack
> Who's Jack? I don't know any Jack

Next install the **power jack** and **switch**. 

<img src="Images/6" width="400"/>

- There are two circular holes next to each other on [*Side-B*](Printed%20Parts/Frame/BBProV25fl_Side-B.stl) of the printer. 
- The black rubber cover for the power jack is optional
- Secure the power jack with the supplied nut
- The power switch will locks into place once pushed in
  
<img src="https://github.com/user-attachments/assets/3d6d6a31-7caf-4dcb-abdb-f1ed99514283" width="400"/>

Here is what it should look like from the other side. 

<img src="https://github.com/user-attachments/assets/77bac97a-cb90-4558-a4f0-0e4bb4c02942" width="400"/>

- Wire the two components as such
- Wrap in electrical tape or use heat-shrink tubing (not supplied) to insulate the connections and avoid accidental shorting
- We opted to solder the wires to the connectors for this build

<img src="https://github.com/user-attachments/assets/4c4e5fe0-e58a-4b74-9332-37aeebc78053" width="400"/>

### Board
> All a'board!

- Install the SKR board by the power switch using 3, **M3x10mm**

<img src="https://github.com/user-attachments/assets/b7ecfd8f-f5dd-46bf-8269-dbd4b9b66b3b" width="500"/>

- Make sure the Micro-USB and MicroSD ports line up with the holes for them in the side panel

<img src="https://github.com/user-attachments/assets/7149403c-ffb8-4952-a30e-437616d1a554" width="400"/>

- Connect the wires from the power switch & power jack to the SKR board as shown below
<img src="https://github.com/user-attachments/assets/341a8c70-fc60-44ff-981f-8a9f0b21cab1" width="400"/>

<img src="https://github.com/user-attachments/assets/a796f87f-1ac0-43b1-a7ee-fe7631c2516e" width="400"/>

### Screen
> AAAAAAAAAAAHHHHHHHHH, oh sorry I thought you said scream

Next we will install the screen.

<img src="https://github.com/user-attachments/assets/7d2010a1-e6ee-433a-97a6-2b42b1cd4d0b" width="500"/>

- Use 4, **M3x10mm** to connect the screen to the [*Screenmount*](Printed%20Parts/Frame/%5Bs%5D_BBProV25fl_Screenmount.stl)

<img src="https://github.com/user-attachments/assets/56344ad5-babf-43a7-845c-54267f22ab2f" width="500"/>

Here is what it should look like. 

<img src="https://github.com/user-attachments/assets/2c9b1930-8b4a-4e23-8fb0-0d9b97458b7b" width="500"/>

- Attach the knob by pushing it onto the silver dial beneath the screen

<img src="https://github.com/user-attachments/assets/af6e648e-cb76-47d7-8f44-9cd0f53df8f0" width="500"/>

<img src="https://github.com/user-attachments/assets/fdc654fa-ed42-4689-9ce5-1be9e89d27ea" width="500"/>

- Plug the wire into the port labeled RS232 on the back of the screen using the black plastic connector that combines all the wires into one

<img src="https://github.com/user-attachments/assets/f9ca34d8-1787-478c-8bad-1660cb3cc499" width="300"/>

<img src="https://github.com/user-attachments/assets/f32a3417-b41a-479b-ab4b-8d5fe66cb84c" width="300"/>

- Attach the [*screen mount*](Printed%20Parts/Frame/%5Bs%5D_BBProV25fl_Screenmount.stl) to the frame by inserting one **M3 Nut** into the hole on the bottom of the frame, next to where it slots into the base 

<img src="https://github.com/user-attachments/assets/597d2b2c-b585-4c7a-b72e-251d67fccc63" width="500"/>

- Insert one **M3x20mm** into the hole on the side of the frame and use it to secure the [*screen mount*](Printed%20Parts/Frame/%5Bs%5D_BBProV25fl_Screenmount.stl)

<img src="https://github.com/user-attachments/assets/a6d614dc-dff0-48c2-993d-31b4e22f030d" width="500"/>

Next use 2, **M3x10mm screws** and 2, **M3 Nuts** to attach the screen mount with the two holes in the top. 

<img src="https://github.com/user-attachments/assets/f8f4b22a-0f02-4fcc-880c-143a53111aa4" width="500"/>

<img src="https://github.com/user-attachments/assets/99af6369-9028-4598-8226-b3acdb63f3a0" width="500"/>

Tada! You have installed the screen!

### Extruder
> I barely know 'er!
- Attach the **gear** to the **Nema 17 stepper motor** ensuring that the **grub screw** is tight against the flat part of the motor shaft
>[!NOTE]
> Make sure the gear fits properly with the rest of the gears in the extruder

<img src="https://github.com/user-attachments/assets/ee6b4935-d054-41bc-b9f8-ac7f15953488" width="300"/>

- Line up the motor with the mounting holes in the side of the frame

<img src="https://github.com/user-attachments/assets/bd6d13f7-7065-4890-9354-b8aff10cd5e3" width="300"/>

- Attach the extruder to the outside of the frame with 4, **M3x10mm** screws

<img src="https://github.com/user-attachments/assets/f627ea61-01b5-446b-9ed1-e5c02fc67d36" width="300"/>

### Belt Tensioner
> Consider loosening or removing after big holiday meals

Next we will build and install the belt tensioners. 
>[!NOTE]
>There are two of these, so do each step twice.

<img src="https://github.com/user-attachments/assets/c6457005-1cc5-4994-9dfa-080abeef1ef4" width="500"/>

- Fit a **M8 Nut** into [*PrintBelt_Pusher-A*](Printed%20Parts/PrintBelt/%5Ba%5D_BBProV25fl_PrintBelt_Pusher-A.stl)/[*PrintBelt_Pusher-B*](Printed%20Parts/PrintBelt/%5Ba%5D_BBProV25fl_PrintBelt_Pusher-B.stl)
- Secure it with a **M8x70mm** Screw 

<img src="https://github.com/user-attachments/assets/df1fb383-9402-4468-b976-6a9a1a05ac0a" width="300"/>
<img src="https://github.com/user-attachments/assets/92e64ce2-4803-4124-9279-d7a819573305" width="500"/>

- Fit another **M8 Nut** into the [*PrintBelt_Nut*](Printed%20Parts/PrintBelt/%5Ba%5D_BBProV25fl_PrintBelt_Nut%5Bx2%5D.stl) and line up with the hole on the [*PrintBelt_Frame-A*](Printed%20Parts/PrintBelt/%5Ba%5D_BBProV25fl_PrintBelt_Frame-A.stl)/[*PrintBelt_Frame-B*](Printed%20Parts/PrintBelt/%5Ba%5D_BBProV25fl_PrintBelt_Frame-B.stl).

<img src="https://github.com/user-attachments/assets/6e03702d-3aa5-464d-9c64-d415d65d8d85" width="500"/>
<img src="https://github.com/user-attachments/assets/c240b288-dc5a-4636-8a0b-98f97797228d" width="400"/>

Congratulations! You have built your tensionsers! They should look like this.

<img src="https://github.com/user-attachments/assets/e39cf16a-80e4-4c52-b760-763699a63cf9" width="500"/>

- There are spots for the tensioners to fit on either side of the base. 

<img src="https://github.com/user-attachments/assets/6782f3f2-decd-4a22-8f90-4d772b28c937" width="500"/>

- Use a **M3x20mm screw** to install both of the tensioners with the curved portion facing downward. 

<img src="https://github.com/user-attachments/assets/d7f2de77-f25e-4956-82bd-a4fd07d89f15" width="500"/>
<img src="https://github.com/user-attachments/assets/ed9512a5-8de4-4748-b3db-ba6e1fe0bee2" width="500"/>

### Rollers
> Not the kind your grandma used to wear

- Wrap both [*rollers*](Printed%20Parts/ZBeltDrive/%5Ba%2Cs%5D_BBProV25fl_Roller%5Bx2%5D.stl) in electrical tape to maintain a better grip on the belt
- We recommend 2 wraps, with the 2nd one helping to hold the first in place 
- Place a **M8 Nut** into the side slot and then inserting a **M8x70 Hex Screw** with a **608ZZ bearing** fully into the [*roller*](Printed%20Parts/ZBeltDrive/%5Ba%2Cs%5D_BBProV25fl_Roller%5Bx2%5D.stl)

<img src="https://github.com/user-attachments/assets/9e3aadef-e4c9-4dc8-8644-2361f7116dfd" width="600"/>
<img src="https://github.com/user-attachments/assets/17879f8c-5dbe-4347-8bf7-3feb78fd261c" width="600"/>
<img src="https://github.com/user-attachments/assets/fc152093-dc8d-498b-9b91-96f2069aff33" width="600"/>
<img src="https://github.com/user-attachments/assets/c8a36d71-9002-4c6f-bf11-f0d818ad1f3c" width="600"/>

- On one of the rollers, install the [*Roller_ZGear*](Printed%20Parts/ZBeltDrive/%5BHT%5D_BBProV25fl_Roller_ZGear.stl) on the screw, before the bearing
<img src="https://github.com/user-attachments/assets/afde2928-e1e8-4733-8c04-ffd2baae0da5" width="600"/>
<img src="https://github.com/user-attachments/assets/e4ae22e8-4ee6-4781-9b66-eb6a80ddd77b" width="600"/>
<img src="https://github.com/user-attachments/assets/6513f526-5d7e-4cb6-b9b4-1e5cb766752e" width="600"/>

### Print Belt
> Personally I prefer leopard

Follow the guide below to make the printbelt. <br>
https://docs.google.com/document/d/13pu9LH_nKmDJY-V2nZXMY8CHur7INB6-9V5sKlAuCuE/edit?usp=sharing

### Z Motor
> OOOOHHHH you mean like the axis

<img src="https://github.com/user-attachments/assets/0b40892e-217d-4f52-80b4-7c3ce20613d7" width="500"/>

- Attach the Z motor to the fram using 4, **M3x10mm screws** 

<img src="https://github.com/user-attachments/assets/3fb7976c-f58f-4e95-9401-5e7e916cd272" width="500"/>

- Make sure the wire port on the motor is facing towards the screen 

<img src="https://github.com/user-attachments/assets/7877d8de-6ce7-4902-9283-c2a2d269ba93" width="500"/>

- Install the [*Nema 17_Z Gear*](Printed%20Parts/ZBeltDrive/%5BHT%5D_BBProV25fl_Nema17_ZGear.stl) onto the motor and then check to make sure it lines up with the gear on the [*Roller_ZGear*](Printed%20Parts/ZBeltDrive/%5BHT%5D_BBProV25fl_Roller_ZGear.stl) we installed on one of the rollers earlier

<img src="https://github.com/user-attachments/assets/5c964e1b-c2df-4af8-b923-84f7bea368fb" width="250"/>
<img src="https://github.com/user-attachments/assets/d71a185e-4428-4ba6-96d3-8a3b8c4009c8" width="500"/>

Improperly fitting vs Properly fitting gears

<img src="https://github.com/user-attachments/assets/4cbc0b8f-7f7b-4984-b562-efb14ed604ee" width="450"/>
<img src="https://github.com/user-attachments/assets/172ade7e-f9cf-4630-b455-d86e6c6c31c1" width="500"/>

- Place a **M3 Nut** into the slot on the side of the frame right above the motor. Repeat on the other side

<img src="https://github.com/user-attachments/assets/230711e7-efb6-4479-b41e-3a5bc8a730e7" width="400"/>
<img src="https://github.com/user-attachments/assets/51d66fe4-46e7-4d7e-bfda-5b9f368a5c47" width="500"/>

- Use a **M3 Nut** and **M3x20mm** screw to attach the [*scraper*](Printed%20Parts/Frame/BBProV25fl_Scraper.stl) in the same manner the screen mount was attached previously
- Use a **M3x10mm** to attach the scraper below the roller, securing into the nuts we previously inserted 

<img src="https://github.com/user-attachments/assets/a0f8708d-9e75-4c7e-93d0-6078a2efaa76" width="500"/>
<img src="https://github.com/user-attachments/assets/050e85e9-5f11-4d8c-854d-8ba158d446f3" width="450"/>

>[!NOTE]
>To complete this guide, we decided to leave the belt off during this step to make it easier to get clear images of the build as it progressed. Even once the printer is built, removing the scraper and replacing the belt is quick and easy. At this point, we suggest you install the Z roller with the belt so it looks like the picture on the right. 

<img src="https://github.com/user-attachments/assets/0c7a9985-c82d-4b31-ace3-f78fa4ebd704" width="500"/>
<img src="https://github.com/user-attachments/assets/2bb28c96-0a7e-42c5-a27f-0e4e4b368a42" width="375"/>

### Y Stop
> Because we said so

- Insert the [*TensionIdlerHolder*](Printed%20Parts/Gantry/Y/%5Ba%5D_BBProV25fl_Y_TensionIdlerHolder.stl) into the [*TensionBody*](Printed%20Parts/Gantry/Y/%5Ba%5D_BBProV25fl_Y_TensionBody.stl) with the larger hole (to accomodate for the screw head) on the same side as the circular indentation on the body
- Make sure your orientation matches the following pictures
- Keep the [*TensionIdlerHolder*](Printed%20Parts/Gantry/Y/%5Ba%5D_BBProV25fl_Y_TensionIdlerHolder.stl)  in place with a **M3x20mm screw**

<img src="https://github.com/user-attachments/assets/15919510-2bae-485b-913d-e8298204de60" width="400"/>
<img src="https://github.com/user-attachments/assets/7af55c58-0bbf-41a4-b603-e724bc4c4f4e" width="400"/>

>[!CAUTION]
>Make sure the configuration of your [*TensionIdlerHolder*](Printed%20Parts/Gantry/Y/%5Ba%5D_BBProV25fl_Y_TensionIdlerHolder.stl)  and [*TensionBody*](Printed%20Parts/Gantry/Y/%5Ba%5D_BBProV25fl_Y_TensionBody.stl) are correct before proceeding.

### Hotend Fan
> For the printer not you ;)

Attach the [*YCar_Bam_Fan*](Printed%20Parts/Gantry/Carriage/%5Ba%5D_BBProV25fl_YCar_Bam_Fan.stl) to the [*YCar_Bam_BeltHolder*](Printed%20Parts/Gantry/Carriage/%5Ba%5D_BBProV25fl_YCar_Bam_BeltHolder.stl) by inserting 2, **M3x10 screws** into the holes indicated in the first image, and through the whole in the second image
- Secure with **M3 Nuts** 

<img src="https://github.com/user-attachments/assets/983b2477-9dfa-4432-8ae9-50a352528a17" width="400"/>
<img src="https://github.com/user-attachments/assets/0addedb7-bd45-4dc7-86bf-5a80da0c1dbf" width="300"/>

Your part should now look like this. 

<img src="https://github.com/user-attachments/assets/e161cee9-e5ef-45d4-b6f4-c7a81139aa65" width="400"/>

- Orient the fan so that the air flow will move towards the air duct on the fan mount, then secure where indicated with zip ties 
<img src="https://github.com/user-attachments/assets/0d54245d-0a52-4fe1-b681-3d7750e7941d" width="400"/>

- Use a zip tie to secure the wires to the side of the carriage 

### Y Gantry
> well it sounds better than support, platform, or bracket

- Insert a **M3 Nut** into this slot on the [*YCar_Bam_Side-A*](Printed%20Parts/Gantry/Carriage/%5Ba%5D_BBProV25fl_YCar_Bam_Side-A.stl)

<img src="https://github.com/user-attachments/assets/8389007d-f2ee-4525-b71f-9ce973659500" width="400"/>

- Attach the carriage to the **linear rail** using 4, **M2x6mm screws**

<img src="https://github.com/user-attachments/assets/40ef57ec-a302-498a-b38c-03a722d43448" width="400"/>

- Insert a **M3 Nut** into the still exposed slot on the [*YCar_Bam_Side-A*](Printed%20Parts/Gantry/Carriage/%5Ba%5D_BBProV25fl_YCar_Bam_Side-A.stl)

<img src="https://github.com/user-attachments/assets/14f45fcf-075b-46d2-b59d-07b6f31b1015" width="400"/>
<img src="https://github.com/user-attachments/assets/ca8fff81-89f2-453d-a82b-0f0ca9a63a19" width="400"/>

- It should line up with the hotend fan like so:

<img src="https://github.com/user-attachments/assets/4ad4f308-e609-4841-a616-053420db988f" width="400"/>

- Insert **M3 Nuts** into the slots indicated on the [*YCar_Bam_Side-B*](Printed%20Parts/Gantry/Carriage/%5Ba%5D_BBProV25fl_YCar_Bam_Side-B.stl)

<img src="https://github.com/user-attachments/assets/690f6a91-35cc-4c6f-8a33-c25ede306f81" width="400"/>
<img src="https://github.com/user-attachments/assets/885f7aad-7a41-429c-9c85-67f06a6d4d6a" width="400"/> 

Next we will install the hotend to the [*YCar_Bam_Side-B*](Printed%20Parts/Gantry/Carriage/%5Ba%5D_BBProV25fl_YCar_Bam_Side-B.stl)

<img src="https://github.com/user-attachments/assets/043df1a4-8de6-4cf5-bd9d-c47bba7ad218" width="400"/>

- Use a **M3x20mm screw** and a **M3 Nut** to attach the hotend to the [*YCar_Bam_Side-B*](Printed%20Parts/Gantry/Carriage/%5Ba%5D_BBProV25fl_YCar_Bam_Side-B.stl)
through the hole shown at the top

<img src="https://github.com/user-attachments/assets/9245b2fb-d5c7-429b-b5fb-7d604090764f" width="400"/>
<img src="https://github.com/user-attachments/assets/125916a8-e388-4fca-99e6-374df99b4a23" width="400"/>

- Make sure the screw goes through the correct hole on the hotend

<img src="https://github.com/user-attachments/assets/566c6d64-adca-411f-997b-366c087e6e37" width="400"/>

- Insert **M3 Nuts** into the holes pictured 

<img src="https://github.com/user-attachments/assets/a499a075-7d23-4e6b-a5f2-79df09ab671f" width="400"/> 
<img src="https://github.com/user-attachments/assets/f126673f-1acb-4d0e-b1c3-26727f3c22a0" width="400"/> 
<img src="https://github.com/user-attachments/assets/ce38e393-e8d7-470e-b894-dedab590ae9e" width="400"/>

- Attach the hotend fan assembly to the rail carriage (this is easier to do one half at a time)
- Use **M3x8mm screws** for the top holes and **M3x10mm screws** for the holes nearest the nozzle. 

<img src="https://github.com/user-attachments/assets/618327e2-cfea-43cf-97ff-cf14b5508c32" width="400"/> 
<img src="https://github.com/user-attachments/assets/2151d359-61cd-47fa-96fa-2de35886458e" width="400"/> 
<img src="https://github.com/user-attachments/assets/fc9a0cba-6c38-422d-a52a-6fae75be56b3" width="400"/> 
<img src="https://github.com/user-attachments/assets/9e267cb4-9877-40e7-ba8b-b59a1467b9f7" width="400"/>

### Hotend
> Again talking about the printer not yours

Next we will install the electrical components to the hotend. 

<img src="https://github.com/user-attachments/assets/809f991b-b64a-46eb-bc87-5248a2eb747f" width="600"/>

- Insert the **thermistor** into the small hole in the block right above the nozzle

<img src="https://github.com/user-attachments/assets/ff5475ce-ca49-4b11-a42a-1a9198113b92" width="400"/>

The thermistor

<img src="https://github.com/user-attachments/assets/25568316-c5b6-4865-913d-e67e055dda5c" width="200"/>

- Run the wire through the channel built into the black **heat break**. 

<img src="https://github.com/user-attachments/assets/db105d7f-f45e-4ee2-8ff4-ba87989831df" width="600"/>

- Place the **heater cartridge** on the front of the block and run the wires through the same channel as the thermistor
- Secure it and the thermistor in place with the **metal clip** 

<img src="https://github.com/user-attachments/assets/816ab2e8-2e75-48d0-932d-365b61ea6904" width="600"/>

### Parts Fan
> Not to be confused with a whole fan. I mean it is a whole fan but it's for cooling parts.

Time to install the **part cooling fan** to the front of the **hotend heatbreak**. 

<img src="https://github.com/user-attachments/assets/079fcc9f-1a05-4524-a414-5f646b13f125" width="600"/>

- Insert **M3 nuts** into these slots of the current assembly 

<img src="https://github.com/user-attachments/assets/31a8047c-203f-441c-9252-5e402a07d6f6" width="400"/>

- Using 2, **M3x20mm screws** on top and 2, **M2.5x12mm** screws on bottom to secure the hotend fan

<img src="https://github.com/user-attachments/assets/70b28acb-eb0b-44fb-b51b-6c837fdbb7d0" width="400"/>
<img src="https://github.com/user-attachments/assets/f6b1fe6c-5bd6-4c34-ac04-bad08b512f06" width="384"/>

### X Gantry
> The breakup was hard on everyone

- Line up the **smooth idlers** with the indicated holes and secure in place with 2, **M3x20 screws**
<img src="(https://github.com/user-attachments/assets/e96993ae-0902-4b96-b806-d7710f0146ad" width="600"/>
<img src="https://github.com/user-attachments/assets/514bbd8f-24d2-4797-9810-8d411b986082" width="600"/>

- Your gantry should now look like this. The yellow boxes indicate where the gantry will be attached to the pair of **linear rails**
- Attach the gantry to the linear rails using 8 **M2x6 screws** (4 for each linear rail) 

<img src="https://github.com/user-attachments/assets/ce6b942d-3be2-42fb-a343-3d55f489169e" width="600"/>
<img src="https://github.com/user-attachments/assets/af106214-e4c4-4e9e-b750-12450851296f" width="600"/>

Here's what it should look like with the rails attached. 

<img src="https://github.com/user-attachments/assets/c467dfec-9481-4607-829e-a9c057e60abd" width="600"/>

>[!Note]
>Unfortunately, we missed taking photos installing the the [*X_RailMount_Side-A*](Printed%20Parts/Gantry/X/%5Ba%5D_BBProV25fl_X_RailMount_Side-A.stl) and [*X_RailMount_Side-B*](Printed%20Parts/Gantry/X/%5Ba%5D_BBProV25fl_X_RailMount_Side-B.stl)
>Attach these printed parts using 4, **M2x8mm screws** and 4, **M2 Nuts**
>

### Combining Axes
> FUSION HA!

<img src="https://github.com/user-attachments/assets/473fdab5-2522-43b9-8af5-a2f951ea1a42" width="600"/>

- Attach the linear rail of the Y axis to the X gantry as shown below, using 2, **M2x8mm screws** and 2, **M2 Nuts**

<img src="https://github.com/user-attachments/assets/21deac05-1ee3-4488-a921-4ea1e36e1021" width="600"/>

- Attach the [*LinearRailReplacement*](Printed%20Parts/Gantry/Y/%5Bany%5D_BBProV25fl_LinearRailReplacment.stl) on the other side of the Y axis in the same way 

<img src="https://github.com/user-attachments/assets/2a9f8729-0ef7-4b5c-a443-c390910b8b3d" width="600"/>
<img src="https://github.com/user-attachments/assets/acf06334-0604-49fc-b51e-eb4bf63ff3b6" width="600"/>

### GT2 Belts
> Gran Turismo 2 was the best one, not sure why people keep bringing up belts tho...

>[!NOTE]
>When installing the GT2 belts, try to get them as tight as possible when you first install them. This will make it easier to get the right tension later. You can precut the belts to 480mm (Y axis) and 290mm (X axis) and trim down when finishing, or you can run a much longer length (even the full uncut belt) to make sure you don't cut your belt too short. Either way you will have some leftover. 
 
- Run the belt through the Y stop, teeth facing toward the idler, and secure the first 3 teeth into the Y gantry

<img src="https://github.com/user-attachments/assets/ca81bfab-3e5d-486d-b96a-9b9ca5ce695f" width="600"/>
<img src="https://github.com/user-attachments/assets/3ed59ce1-2239-4a49-995e-2eba90a14c45" width="600"/>
<img src="https://github.com/user-attachments/assets/9fc91996-f9ca-4c6b-aebe-649cc2ac882f" width="280"/>

Next install the **Y motor** onto the X gantry. 

<img src="https://github.com/user-attachments/assets/6c5f6aa5-57dd-4189-9924-8caff77a258f" width="600"/>

- Install the **pulley** onto the motor shaft, making sure the **grub screw** is on the flat face of the shaft

<img src="https://github.com/user-attachments/assets/579fe1b6-f6c7-4411-b6df-45b265518b7c" width="220"/>
<img src="https://github.com/user-attachments/assets/071f58c6-990e-44a0-ba01-6ac72f8bc03d" width="400"/>

- Install the motor onto the X gantry in the position that is closest to the hotend using 4, **M2.5x8mm** screws

<img src="https://github.com/user-attachments/assets/e293f010-29ba-4cc2-8273-37c5731d21a3" width="600"/>
<img src="https://github.com/user-attachments/assets/e0f9cdb4-9569-489d-b069-4c3259ad0b1a" width="600"/>

- Rrun the belt through the X gantry and around the pulley

<img src="https://github.com/user-attachments/assets/091e5ef2-aa74-447c-a5ac-95f2abefe222" width="600"/>

- Cut the belt so that it fits into the remaining teeth and secure in place with a zip tie

<img src="https://github.com/user-attachments/assets/a53127ae-119e-4037-a419-d7ed17b72d23" width="400"/>
<img src="https://github.com/user-attachments/assets/28f8cf35-d81d-4924-b71d-981dca9f7f46" width="300"/>


>[!Caution]
>The printed parts shown for the X axis belt attachment steps are not the most current up to date versions, we will update the photos when we can. The main difference is that instead of mounting the GT2 belt directly to the X_RailMount_Side-A & X_RailMount_Side-B like in our instructions below you will attach the belt using the [*X_PivotArm*](Printed%20Parts/Gantry/X/%5Ba%5D_BBProV25fl_X_PivotArm%5Bx2%5D.stl) and [*X_Pivot Clamp*](Printed%20Parts/Gantry/X/%5Ba%5D_BBProV25fl_X_PivotClamp%5Bx2%5D.stl)
>

- Run the belt for the X Axis as seen below, going through the lower hole on the right

<img src="https://github.com/user-attachments/assets/184d2fd3-e540-48bd-bcb0-10c5ce702727" width="600"/>

- Loop the belt around the outside, through the second hole, and then interlock the teeth and pull till it is firmly locked into the first hole (this can be a bit tricky and may take several tries to get it just right) 

<img src="https://github.com/user-attachments/assets/5b1eb4da-ea42-4e53-a3b7-333254c69d3e" width="400"/>

- Push the belt to make space for the pulley on the X axis motor (prepared identically to the Y axis motor)

<img src="https://github.com/user-attachments/assets/7cc1e6fb-92ca-4021-b8f4-b606b99887a3" width="600"/>
<img src="https://github.com/user-attachments/assets/ce775bd0-d561-49ab-b603-137e55a0fcb3" width="600"/>

- Attach the X belt tensioner on the left side of the assembly using a **M3x20 screw** 

<img src="https://github.com/user-attachments/assets/386532a5-c28e-4e81-bea2-51252f9848a4" width="600"/>

- Run the belt through the bottom slot and then through the top slot and secure with a zip tie

<img src="https://github.com/user-attachments/assets/7c3b5091-44cc-45f8-96d3-13e6a8b740d3" width="400"/>
<img src="https://github.com/user-attachments/assets/1e283ef4-9fca-458f-991e-3b69365d3373" width="400"/>

- Insert a **M3x10mm screw** and **M3 Nut** to the hole in the top of the tensioner. This can be used to adjust the belt tension as needed. 

<img src="https://github.com/user-attachments/assets/a6945aa1-3e4d-4695-9ad6-9b68a0750fe7" width="400"/>
<img src="https://github.com/user-attachments/assets/4dfd4188-40bb-49b2-b5ca-bff99d1595fa" width="380"/>
<img src="https://github.com/user-attachments/assets/12b3c39f-a960-44a5-bc6e-b6b34ff3f06d" width="400"/>

### Hotbed
> Something something pun about a bed and blankets making it warm...

<img src="https://github.com/user-attachments/assets/68541709-a9e4-49b4-adad-854df8226e4b" width="600"/>

- Stick the **bed heater** onto the **aluminum bed** like so
  
>[!CAUTION]
>Make sure you stick the pad onto the correct side. There should be no indents around the holes for the screw heads. 

<img src="https://github.com/user-attachments/assets/cbd421c4-3ead-4061-8cbd-e0d473481145" width="400"/>

- Attach the **aluminum bed** using 3, **M3x10mm** to the [*UnderbedOrBed*](Printed%20Parts/ZBeltDrive/%5BHT%5D_BBProV25fl_UnderbedOrBed.stl) using 3, **M3 Nuts** on each screw as spacers

<img src="https://github.com/user-attachments/assets/591c3b34-babb-4eeb-850f-39108be2516c" width="400"/>

- The bed will fit into the base like this:

<img src="https://github.com/user-attachments/assets/8c6ccaba-0652-40a8-a365-d0bc667e1c3d" width="400"/>

### Wiring
> It's electric, Boogie woogie, woogie! Well, not yet but soon^TM^.

Let's get those wires connected!

>[!NOTE]
>This hole located on the right of the screen holder is where all wires from the outside of the base should be routed through. This includes the X and Y motors, both fans, the thermistor, and heater. <br>
><img src="https://github.com/user-attachments/assets/12361468-ed2c-4448-af0b-ff4cae994208" width="400"/>

>[!TIP]
>Wire management can be difficult and can take some practice to get good at. The most important thing is making sure the wires are easily identifiable and are not in the way of any moving components. 

- Start by plugging in the motors
- There are 5 (slots) on the side of the board closest to the screen 

<img src="https://github.com/user-attachments/assets/44517b25-4dcd-4e2f-b78d-2425e41cd173" width="400"/>

- From left to right is the X motor, Y motor, Z motor, and Extruder. At this time you should also install the 3 red jumpers pictured in the bottom right

<img src="https://github.com/user-attachments/assets/8eefe581-1154-454e-9599-c97d1fa577c8" width="400"/>

- Plug both fans in. ***NOTE:*** *The wires in our kit were a bit short and we had to extend them. This is now fixed in the kits so your wire colors likely will not match the photos.* The hotend fan is shown with blue and green wires, while the parts fan is shown with red and black 

<img src="https://github.com/user-attachments/assets/5853aa3d-db09-489a-88de-4ab71fc61c9f" width="400"/>

- Install the heater cartridge wires into the screw terminal located right next to them (orientation is not important)

<img src="https://github.com/user-attachments/assets/d5976f16-fded-4f93-94f4-ca0aa67c6ba7" width="400"/>

- Both thermistors are plugged in on the opposite side of the board. ***NOTE:*** *The wires in our kit were a bit short and we had to extend them. This is now fixed in the kits so your wire colors likely will not match the photos.* The hotend thermistor is shown with blue and green wires, while the bed thermistor has red and black. 

<img src="https://github.com/user-attachments/assets/d822a788-b5ca-4527-b237-6f86a388fbf8" width="400"/>

- The bed heater wires can be installed in the screw terminal next to where we installed the hotend (orientation does not matter)

<img src="https://github.com/user-attachments/assets/f50b4003-296f-44fe-8f27-cf78830ddc88" width="400"/>

- Plug the screen wires into the freestanding pins located above the jumpers 

<img src="https://github.com/user-attachments/assets/2689e484-922c-4ec5-a81e-77556d32ac77" width="400"/>

### Print Belt
> The end of the road! I mean technically its a loop so there is no end

Now that all the insides are done we can do final assembly of the belt. This is straightfoward, but can be a bit tricky to make everything fit right. If things aren't fitting right or moving smoothly DO NOT force anything, try sanding at any pain points and try again.

<img src="https://github.com/user-attachments/assets/448e1352-1fc4-4751-bfb9-4a574493e3ce" width="600"/>

- Place the heatbed inside the belt, with the plastic prongs facing upwards and slot them into the frame

<img src="https://github.com/user-attachments/assets/65515845-0a6a-4b5a-8303-31e7a3c4644e" width="600"/>

- Slide the other roller into the belt and maneuver it into the curved slots in the frame
- Use the belt tensioners to get the belt tensioned just right

<img src="https://github.com/user-attachments/assets/829bb469-5317-4144-abcf-f764c36e8209" width="600"/>

### Finished Printer
- Attach the bowden tube from the extruder to the hotend and you have finished the physical build of your printer!

<img src="https://github.com/user-attachments/assets/de2d04fa-db18-4e3f-96c5-4b7619084896" width="600"/>
