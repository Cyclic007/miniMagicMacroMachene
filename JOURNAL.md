# miniMagicMacroMachene

#### May 16 (part 1) (1.5hr)

##### the start

The idea for this project is a small macro pad that can be used with a laptop effectively

Today I am making a BOM and finding the things that are needed for the PCB design and starting on the 3d Model



#### May 16(part 2) (4 hr)

created the PCB and finished PCB and found 

- https://www.digikey.com/en/products/detail/1N4148/1N4148FS-ND/458603
- https://cherry.saas.contentserv.com/admin/rest/document/30?ContextIDs=15343&Language=1

these are the parts I will be using and hopefully 3d print the rest. 

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2a4f2af618b56019a9ad0f7acd084e40a72afda3_image.png)



#### May 17 (3.5hr)

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



#### May 19 

So I learned that I have the wrong pinout for the pi Pico 2 and on the pcb have switches connected to the ground pins and not the data pins

the pinout :

	https://datasheets.raspberrypi.com/pico/Pico-2-Pinout.pdf

Fixed the pinout problem and also fixed my traces so that rows are on top while collems are on bottom 

Also fixed my bord cutout 

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/f991de79bde488d023c933982953797590d9f2c7_image.png)


![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/207465efb79e7bfdae7e1e5a1582351e55a2cdda_image.png)