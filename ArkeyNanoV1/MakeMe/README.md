# Parts Needed
- PCB
- 18 Kailh hot swap sockets
- 18 of your preferred switches compatible with the Kailh sockets
- 18 keycaps to fit the switches
- Raspbery Pi Pico

# PCB
Just upload the .zip file in the PCB folder to your preferred PCB manufacturer's site.

### Assembly
- Solder the sockets to the back of the PCB (the side without the logo)
- Solder the Pico to it's pads on the front of the PCB. This will be surface mount, do not use headers or a pico with headers unless you're going to custom design your own case.
- Insert your keyswitches into the sockets
- Put your keycaps on the switches

# Firmware
Hold the bootsel button on the pico while plugging it into your computer
Drop the .uf2 file from the Firmware folder onto the pico. It will reboot. Once it finishes rebooting, your controller should function. 

# Case
There are 2 STL files in the Case folder, print both. You'll need 3.5mm thickness screws of your preferred type to assemble the controller with case. 

### Assembly
There are 2 arrows on the bottom plate, they point up and left. Place them on the left side.
Place the PCB onto the bottom plate.
Place the top plate over the PCB and bottom plate. The bottom of the bottom plate "should" be flush with the bottom lip of the top plate.
Insert your fasteners through the holes on the bottom plate and attach however you prefer. I like to use flat head screws going through the bottom with cap nuts on the top, allowing me access to internals by hand. And I put rubber feet over the head of the screws.

