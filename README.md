# Clap404's Legacy Mods

This repo contains the mods I made for my custom [Voron Legacy](https://vorondesign.com/voron_legacy).
It's mainly made from the remains of an anet AM8 and a sidewinder X1 for the electronics, which is why its dimensions are :
- build volume : 200 x 300 x 270
- frame size : 380 x 480 x 440

## Basement Electronics Enclosure

This mod allows you to mount the eletronices on two 8mm rods (lead screws, smooth rods, threaded M8 rod, etc.) at the bottom of your printer, below the heated bed.
![bottom view](/basement_enclosure/img/bottom_view.jpg?raw=true "bottom view")
![closed view](/basement_enclosure/img/closed_view.jpg?raw=true "closed view")

### Note

- You **will** have to edit the CAD to make this work for you.
- My printer is way longer (on the Y axis) than stock, so you may not be able to fit eveything if yours is shorter.
- I attached some components under the supporting rods, which brings the total height required to fit everything to 90mm. I have to raise the printer 10mm because i'm using 2040 extrusions, you'll need to raise it 30mm if you use 2020 extrusions, but you can choose to only attach things on top of the rods, using only 60mm.

### BOM

| description                   | quantity	| sourcing (non affiliate) 	|
|-------------------------------|---------------|-------------------------------|
| 8 mm rods of some kind	| 2		| your spare part bin / local hardware store |
| M5x16 BHCS screw		| 4		| same as voron's		|
| M5 post install T-nut		| 4		| same as voron's		|
| 16mm round push button	| 2		| [Aliexpress](https://fr.aliexpress.com/item/4001291695467.html)	|
| C14 fused socket w/ two poles switch	| 1	| [Aliexpress](https://fr.aliexpress.com/item/32706948395.html)		|
| 5x4 heat set inserts (for SSR)| 2		| same as voron's		|
| m3 screws (for mainboard)	| 4		| same as voron's 		|
| m2 plastic screws (for raspberry)	| 4	| same as voron's		|

## Z motor pulley box 

This mod is inspired by the v0.0 lead screw mechanism. It uses two pulleys and a loop belt to transfer the motion from the motor to the screw

### Features

- 1:2 reduction in the default configuration (provides no real benefit)
- avoids using a coupler, ensuring the lead screw is straight
- saves z-travel compared to using a coupler

![top view](/z_motor_pulleybox/img/top_view.jpg?raw=true "top view")
![bottom view](/z_motor_pulleybox/img/bottom_view.jpg?raw=true "bottom view")

### Note

- It should be possible to add 2 more holes around the lead screw hole, to be able to mount this sideways

### BOM

this is the bom per pulley box (you probably neet 2)

| description                   | quantity	| sourcing (non affiliate) 	|
|-------------------------------|---------------|-------------------------------|
| M4x16 screw		        | 2		||
| m3x30 screw		        | 8		||
| m3x5 heat set inserts		        | 4		||
| KFL08 bearing		        | 1		||
| GT2 Belt Loop (6mm wide) - 188mm| 1		||
| 20t GT2 pulley | 1		||
| 40t GT2 pulley | 1		||
| (optional) F688-ZZ        | 1		||
| (optional) m3 washers		        | 8		||
