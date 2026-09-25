# KuromiOled
# OledWEsp

OledWEsp stands for An Oled display with Esp32-c3 all put in a compact case to make it good for travelling around with as a keychain
It has a esp32-c3-super-mini which was the smallest devboard i could find for a cheap price. 
It uses a 450mah Battery with a tp4056 charging module
It uses a 1.3 inch oled display which has a cute kuromi animation
I made it to give it to my sister as a gift!
Might add wifi later
Made in Forge - forge.hackclub.com Tier3 Project.

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


# bill of materials

# BOM

| # | Component | Qty | Price (INR) | Price (USD) | Link |
|---:|---|---:|---:|---:|---|
| 1 | 1.3" I2C OLED Display — White | 1 | ₹319 | $3.32 | [Robu](https://robu.in/product/1-3-inch-i2c-oled-display-module-4-pin-white/) |
| 2 | ESP32-C3 Development Board with Soldering | 1 | ₹279 | $2.90 | [Robu](https://robu.in/product/esp32-c3-development-board-with-soldering/) |
| 3 | 1.5–4.2V → 5V Boost Converter | 1 | ₹119 | $1.24 | [Robu](https://robu.in/product/1-5v-1-8v-2-5v-3v-3-3v-3-7v-4-2v-to-5v-boost-voltage-conversion-module-with-soldering/) |
| 4 | TP4056 1A Li-Ion Charger + Protection | 1 | ₹19 | $0.20 | [Robu](https://robu.in/product/tp4056-1a-lipo-battery-charging-board-micro-usb-with-current-protection/) |
| 5 | WLY52535 3.7V 450mAh 1S LiPo | 1 | ₹299 | $3.11 | [Robu](https://robu.in/product/450mah-pcm-protected-micro-li-po-battery/) |
| 6 | 3×7cm Double-Sided Prototype PCB | 1 | ₹69 | $0.72 | [Robu](https://robu.in/product/3-x-7-cm-universal-pcb-prototype-board-double-side-2pcs/) |
| 7 | 1×40 Pin 2.54mm Long Female Header | 1 | ₹98 | $1.02 | [Robu](https://robu.in/product/1x40-pin-2-54mm-straight-long-female-strip-connector/) |
| 8 | Noel 60/40 Solder Wire 1mm 50g | 1 | ₹309 | $3.22 | [Robu](https://robu.in/product/solder-wire-1-00mm-50gm/) |
| 9 | BAKON 900M-T-I Replacement Soldering Tip | 1 | ₹115 | $1.20 | [Robu](https://robu.in/product/bakon-soldering-iron-tip-900m-t-i/) |
| 10 | Multitec 150B Wire Stripper & Cutter | 1 | ₹60 | $0.62 | [Robu](https://robu.in/) |
| 11 | 24 AWG Solid-Core PVC Wire — Red | 2m | ₹20 | $0.21 | [Robu](https://robu.in/) |
| 12 | 24 AWG Solid-Core PVC Wire — Black | 2m | ₹20 | $0.21 | [Robu](https://robu.in/) |
| 13 | 24 AWG Solid-Core PVC Wire — White | 2m | ₹20 | $0.21 | [Robu](https://robu.in/) |
| 14 | 2mm Heat-Shrink Sleeve — Black | 2 | ₹20 | $0.21 | [Robu](https://robu.in/) |
| 15 | 2mm Heat-Shrink Sleeve — Red | 2 | ₹24 | $0.25 | [Robu](https://robu.in/) |
| 16 | 3mm Heat-Shrink Sleeve — Black | 2 | ₹12 | $0.12 | [Robu](https://robu.in/) |
| 17 | 3mm Heat-Shrink Sleeve — Red | 2 | ₹16 | $0.17 | [Robu](https://robu.in/) |
| 18 | 4mm SPDT 1P2T Slide Switch | 4 | ₹11.40 | $0.12 | [Robu](https://robu.in/) |
| 19 | Insulating Tape — Yellow | 1 | ₹23 | $0.24 | [Robu](https://robu.in/) |
| 20 | M2 × 5mm Phillips Pan-Head SS304 Screw | 10 | ₹20 | $0.21 | [OnlyScrews](https://onlyscrews.in/collections/m2-screws) |
| 21 | M2 × 3mm Brass Threaded Insert | 10 | ₹18 | $0.19 | [OnlyScrews](https://onlyscrews.in/products/m2-x-3mm-brass-threaded-inserts) |
| 22 | 3D-Printed Case | 1 | ₹0 | $0.00 | Self-made |
| | **Total** | | **₹1,890.40** | **$19.68** | |

ROBU HAS A POLICY OF ATLEAST BUYING 10 RUPEES WORTH OF THE PRODUCT thats why i had to buy extra quantities for some like the heat shrink tubes etc


# CART PICS

