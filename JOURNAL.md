---
title: "MiniMagicMacroMachene"
author: "Cyclic"
description: "A wireless macro pad made to be used with autoHotKey"
created_at: "2025-5-16"
---

#### May 16 (part 1) Starting


The idea for this project is a small macro pad that can be used with a laptop effectively

Today I am making a BOM and finding the things that are needed for the PCB design and starting on the 3d Model

**Total Time Spent: 1.5 hr**

#### May 16(part 2) worked on PCB

created the PCB and finished PCB and found 

- https://www.digikey.com/en/products/detail/1N4148/1N4148FS-ND/458603
- https://cherry.saas.contentserv.com/admin/rest/document/30?ContextIDs=15343&Language=1

these are the parts I will be using and hopefully 3d print the rest. 

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2a4f2af618b56019a9ad0f7acd084e40a72afda3_image.png)

**Total Time Spent: 4 hr**

#### May 17 finding parts and failing to make the case

Found venders for PCB parts and found what key switches I am going to use

- https://www.pishop.us/product/raspberry-pi-pico-2/?src=raspberrypi
- https://www.digikey.com/en/products/detail/onsemi/1N4148/458603
- https://mechanicalkeyboards.com/products/cherry-mx2a-black-60g-linear?variant=48014721286444

also found pricing for the parts 

also got a quote for the PCB of 20.06 from PCBway (including shipping)

Found a plugin that will make creating the case infinitely easier allowing communication between freecad and Kicad 

tryed useing FreeCad to make case and am not doing very well at it 

Found a tool called turbocase that generates a scad file for a case for a pcb and I used it to generate the bottom case

also made the BOM

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/d4aed93295c08d1123759227e800be9debfb4fee_image.png)

**Total Time Spent: 3.5 hr**


#### May 19 finishing and finsing the stuff I did wrong

So I learned that I have the wrong pinout for the pi Pico 2 and on the pcb have switches connected to the ground pins and not the data pins

the pinout :

	https://datasheets.raspberrypi.com/pico/Pico-2-Pinout.pdf

Fixed the pinout problem and also fixed my traces so that rows are on top while collems are on bottom 

Also fixed my bord cutout 

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/f991de79bde488d023c933982953797590d9f2c7_image.png)


![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/207465efb79e7bfdae7e1e5a1582351e55a2cdda_image.png)


also starting on the case for the pcb useing fusion360 because freecad is driveing me crazy


created the case for the PCB and finished modeling

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/d83f64d1468e36552dbad9a09bb2207f488d73d4_image.png)

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/01fa173185cb39b1c125f12657aa8aef534b38cb_screenshot_2025-05-19_104359.png)

also starting the firmware using QMK  

I am going to assighn the keys on the keybord to func keys 13 through 21 inclusive

the key layout JSON is in QMKlayout.JSON

also updated the BOM

I found that QMK does not support the rPI pico 2 series but the rPI Pico 1 has the same pinout so I am changeing to useing the PI Pico 1w

Setup the firwere jsons and things and trying to compile

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/477c8773aff9165533b1400a3b3218a7c8f698f3_image.png)

Finished the firmwere

**Total Time Spent: 5.5 hr**
