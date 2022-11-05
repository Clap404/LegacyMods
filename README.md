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
