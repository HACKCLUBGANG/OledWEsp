# KuromiOled
# OledWEsp

OledWEsp stands for An Oled display with Esp32-c3 all put in a compact case to make it good for travelling around with as a keychain
It has a esp32-c3-super-mini which was the smallest devboard i could find for a cheap price. 
It uses a 450mah Battery with a tp4056 charging module
It uses a 1.3 inch oled display which has a cute kuromi animation
I made it to give it to my sister as a gift!
Might add wifi later
Made in Forge - forge.hackclub.com Tier3 Project.
<img width="577" height="490" alt="image" src="https://github.com/user-attachments/assets/b26fd0a5-bce0-4752-92bf-40882f91e930" />

# CASE

<img width="460" height="466" alt="image" src="https://github.com/user-attachments/assets/7b06f0bf-7bfa-4b74-a428-a7004259ff62" />
<img width="611" height="311" alt="{27069CBD-FDC9-4202-85EB-EC40A4797EC0}" src="https://github.com/user-attachments/assets/feb7bd55-fac4-4bfb-89fa-5f55e53295ab" />
<img width="334" height="430" alt="image" src="https://github.com/user-attachments/assets/739bead2-e8e9-4254-b4d0-1a529cb7d5a7" />
<img width="464" height="450" alt="image" src="https://github.com/user-attachments/assets/2016618e-0092-4299-899d-ad9472e896eb" />
<img width="406" height="479" alt="image" src="https://github.com/user-attachments/assets/d1884e4d-00c1-4cc5-8b9b-1d178208820b" />

# Schematics
<img width="916" height="510" alt="image" src="https://github.com/user-attachments/assets/55d3e920-f962-4848-b324-9406e9defcd5" />

# Assembly
after buying all of the components follow these step to assemble your own oled keychain

1st step is 3d printing the parts. Download the print.step file from cad folder in this repository slice it and print it out
2nd step is putting the oled in the 3d part first
Tilt it at this angle and out it in the hole i made 

<img width="636" height="505" alt="image" src="https://github.com/user-attachments/assets/9b1424c6-9020-44ad-a94a-1af27ada8bba" />
<img width="466" height="467" alt="image" src="https://github.com/user-attachments/assets/0748e6f1-fe22-47e6-b93d-49afd1e84a62" />
<img width="638" height="434" alt="image" src="https://github.com/user-attachments/assets/eec6b8e4-4a04-4716-8147-4cf1d630a696" />

Then straighten the oled and slide it in the case like this
<img width="647" height="330" alt="{54DE5FAB-DECF-4AEF-854F-02B2FB19FE32}" src="https://github.com/user-attachments/assets/90614e5a-c6e9-4da9-9311-ff64d353d25c" />
<img width="573" height="283" alt="image" src="https://github.com/user-attachments/assets/abaa3887-3d0c-4b6a-976d-8433746ec6b9" />

PLACE THE OLED IN THIS WAY SO THAT THE SCREEN IS LIKE THIS
<img width="363" height="460" alt="image" src="https://github.com/user-attachments/assets/233abef4-73d9-42c0-a28e-059b1a13e1c4" />
from inside the case add hot glue or tape to make it not move.

Next step is soldering the esp32 board and the female 4 pin connector for the oled to the prototype board board
cut the proto board to the size of 13 x 10 holes
<img width="421" height="459" alt="{BF238F17-1847-4C8C-B080-DE1D6C71CB80}" src="https://github.com/user-attachments/assets/9df6eee6-981c-41b4-a10c-a99b8b8274c5" />

solder them in this way
<img width="501" height="491" alt="image" src="https://github.com/user-attachments/assets/8d76b26d-d1da-4399-9b8f-b446c1c9e130" />
<img width="444" height="480" alt="image" src="https://github.com/user-attachments/assets/447863af-543c-4eee-a18d-9b58bf24f5b3" />

 <img width="559" height="430" alt="image" src="https://github.com/user-attachments/assets/fc7bdace-ace6-4b30-916d-17b7d37add45" />

 here u have to connect the oled by looking at the schematics that are shared in this use the wires and heat shrink tubes to protect the wires and conenct them
 <img width="559" height="430" alt="image" src="https://github.com/user-attachments/assets/894f49f5-97d7-4117-85c1-6f0a9fdd36c8" />

 Next step is to solder the connections of the tp4056 module and esp32
 The BOOST MODULE 3dmodel was not found so i didnt add it to the 3d model but u have to connect it according to the schematics and put it in the case it is small and can fit anywhere 
 make the wires a bit longer because the batery will go between the tp4056 module and the pcbboard
<img width="561" height="394" alt="image" src="https://github.com/user-attachments/assets/d62c83f3-a52a-4efe-a0ea-d7cf44f4990c" />


 Next step is to add the battery
 use tape to stick the battery to the board like this 
 and stick the tp4056 module on top of it
<img width="391" height="303" alt="{9CC12949-A684-44E9-BA49-98179E08D007}" src="https://github.com/user-attachments/assets/ea2037f0-d1ab-4688-9221-11d90f83ebf8" />
<img width="315" height="283" alt="image" src="https://github.com/user-attachments/assets/5d1e272b-203c-4473-a6a7-768f56d56aba" />
<img width="461" height="351" alt="image" src="https://github.com/user-attachments/assets/4aa933d5-9056-48d1-be63-521bcf9245c6" />

put the switch in the hole too i couldnt find a 3d model for it then line up the usb ports with the slots in the 3d print and attach the female 4 pin connector with the oled screen. 
Then the inner parts are done

Now for the screws part u have to use a soldering iron to make the brass inserts hot enought to melt the holes i made for the brass inserts 
place the insert like this
<img width="262" height="316" alt="image" src="https://github.com/user-attachments/assets/01d20c8a-7c70-4db2-9446-33855b454df0" />
Use the soldering iron and push it in the hole 
<img width="397" height="470" alt="image" src="https://github.com/user-attachments/assets/870773d0-2b3e-4b6a-ba08-61290c618736" />

put this piece in and stick it using glue to cover the hole on the bottom 
<img width="176" height="321" alt="image" src="https://github.com/user-attachments/assets/e0ccd183-fc6c-45cd-ab6c-6c8871d633da" />

AND UR OLED KEYCHAIN IS READY!!!

Do this with all 4 

Then put the back lid on and screw the holes in the inserts till tight so that theres no wiggle wiggle

AND UR OLED KEYCHAIN IS READY!!!
<img width="577" height="490" alt="image" src="https://github.com/user-attachments/assets/b26fd0a5-bce0-4752-92bf-40882f91e930" />

# BOM

| # | Item | Specification / Color | Qty | Price (INR) | Link |
|---:|---|---|---:|---:|---|
| 1 | 1.3" I2C OLED Display | White, 4-Pin | 1 | ₹319.00 | [Robu](https://robu.in/product/1-3-inch-i2c-oled-display-module-4-pin-white/) |
| 2 | ESP32-C3 Development Board | With soldering | 1 | ₹279.00 | [Robu](https://robu.in/product/esp32-c3-development-board-with-soldering/) |
| 3 | Boost Converter | 1.5–4.2V → 5V | 1 | ₹119.00 | [Robu](https://robu.in/product/1-5v-to-5v-boost-voltage-conversion-module/) |
| 4 | TP4056 Charger | 1A Li-Ion Charger + Protection, Micro-USB | 1 | ₹19.00 | [Robu](https://robu.in/product/tp4056-1a-lipo-battery-charging-board-micro-usb-with-current-protection/) |
| 5 | WLY52535 LiPo Battery | 3.7V 450mAh, 1S | 1 | ₹299.00 | [Robu](https://robu.in/product/450mah-pcm-protected-micro-li-po-battery/) |
| 6 | Prototype PCB | 3×7cm, Double-Sided | 1 | ₹69.00 | [Robu](https://robu.in/product/37-cm-universal-pcb-prototype-board-double-sided/) |
| 7 | Long Female Header | 1×40 Pin, 2.54mm | 1 | ₹98.00 | [Robu](https://robu.in/product/1-40-pin-2-54m-straight-long-female-berg-strip-connector-pack-of-5/) |
| 8 | Female Header | 1×40 Pin, 2.54mm | 1 | ₹13.00 | [Robu](https://robu.in/product/2-54mm-1x40-pin-female-single-row-header-strip-pack-of-10/) |
| 9 | Noel Solder Wire | 60/40, 1mm, 50g | 1 | ₹309.00 | [Robu](https://robu.in/product/solder-wire-1-00mm-50gm/) |
| 10 | BAKON Soldering Iron Tip | 900M-T-I | 1 | ₹115.00 | [Robu](https://robu.in/product/bakon-soldering-iron-tip-900m-t-i/) |
| 11 | Multitec Wire Stripper & Cutter | 150B | 1 | ₹60.00 | [Robu](https://robu.in/product/multitec-150b-wire-stripper-and-cutter/) |
| 12 | 24 AWG Wire | Solid Core PVC, Red | 2m | ₹20.00 | [Robu](https://robu.in/product/24-awg-solid-core-insulated-wire-pvc-red/) |
| 13 | 24 AWG Wire | Solid Core PVC, Black | 2m | ₹20.00 | [Robu](https://robu.in/product/24-awg-solid-core-insulated-wire-pvc/) |
| 14 | 2mm Heat-Shrink | Black | 2 | ₹20.00 | [Robu](https://robu.in/product/heat-shrink-sleeve-2mm-black-industrial-grade-woer-hst/) |
| 15 | 2mm Heat-Shrink | Red | 2 | ₹24.00 | [Robu](https://robu.in/product/heat-shrink-sleeve-2mm-red-industrial-grade-woer-hst/) |
| 16 | 3mm Heat-Shrink | Black | 2 | ₹12.00 | [Robu](https://robu.in/product/heat-shrink-sleeve-3mm-black-industrial-grade-woer-hst/) |
| 17 | 3mm Heat-Shrink | Red | 2 | ₹16.00 | [Robu](https://robu.in/product/heat-shrink-sleeve-3mm-red-industrial-grade-woer-hst/) |
| 18 | 4mm SPDT 1P2T Slide Switch | — | 4 | ₹11.40 | [Robu](https://robu.in/product/4mm-spdt-1p2t-slide-switch-pack-of-10/) |
| 19 | Insulating Tape | Yellow | 1 | ₹23.00 | [Robu](https://robu.in/product/insulating-tape-yellow%ef%bc%89/) |
| 20 | Curved Tweezers | ESD-15 | 1 | ₹35.00 | [Robu](https://robu.in/product/curved-tweezers-esd-15/) |
| 21 | M2 × 3mm Brass Threaded Insert | Brass | 10 | ₹18.00 | [OnlyScrews](https://onlyscrews.in/products/m2-x-3mm-brass-threaded-inserts) |
| 22 | Micro USB Cable | 50cm, for TP4056 | 1 | ₹39.00 | [Robu](https://robu.in/product/50-cm-micro-usb-cable/) |
| 23 | USB Type-C Cable | 1m, Fast Charging/Data Transfer | 1 | ₹87.00 | [Robu](https://robu.in/product/type-c-usb-cable/) |
| 24 | 3D-Printed Case | Self-made | 1 | ₹0.00 | — |
| 25 | M2 × 5mm Phillips Screw | SS304 | 10 | ₹20.00 | [OnlyScrews](https://onlyscrews.in/collections/m2-screws) |

**Total: ₹1,925.40**

> Robu minimum order value: ₹10 per item.
ROBU HAS A POLICY OF ATLEAST BUYING 10 RUPEES WORTH OF THE PRODUCT thats why i had to buy extra quantities for some like the heat shrink tubes etc


# CART PICS

ONLY SCREWS
<img width="823" height="536" alt="image" src="https://github.com/user-attachments/assets/3a299f39-b011-46d0-aa85-162b55b439d0" />

ROBU.IN

<img width="982" height="549" alt="image" src="https://github.com/user-attachments/assets/fd6c3a8d-8678-4e1e-97cf-1681d4c317ee" />
<img width="1037" height="597" alt="{0B7D5FEC-286B-403A-B581-89F57651FF1B}" src="https://github.com/user-attachments/assets/1ee52e41-245c-48ad-982e-e0e17ce1eeb6" />
<img width="646" height="591" alt="image" src="https://github.com/user-attachments/assets/526c48b7-fa26-4f10-a90f-3497bd6872e1" />
<img width="648" height="537" alt="{460EA0BD-C1D5-4DEF-9230-A2A4932FEC1B}" src="https://github.com/user-attachments/assets/0fee2c08-54c0-458d-8941-1599e4278f8b" />
<img width="653" height="559" alt="image" src="https://github.com/user-attachments/assets/83da2f1d-9c5c-4c2a-9043-5d3a99df82bc" />
<img width="651" height="352" alt="image" src="https://github.com/user-attachments/assets/1acb26a2-6b92-439a-b61c-371b89aa3ee2" />

# CREDITS
CREDITS TO https://www.oledanimationmaker.com/ for convering a mp4 file to oled code for this project.
