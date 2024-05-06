# bitcrane
![the render](doc/bitcrane.png "Render")

introducing the bitcrane. a quick tool to spit bytes at an Antminer hashboard over USB (and control fans & PSU).

uses the [FTDI FT4232HQ](https://ftdichip.com/products/ft4232hq/)

- Updated the BOM (and some parts) to make this compatible with PCBA from [jlcpcb.com](https://jlcpcb.com). 
	- Send them `bitcrane BOM JLCPCB.csv` and `bitcrane-all-pos.csv` from the Manufacturing Files folder.
	- JLCPCB Doesn't stock the EMC2305 (U4) and has a terrible price on the FT4232HQ (U1), so you should prolly assemble these yourself. 
