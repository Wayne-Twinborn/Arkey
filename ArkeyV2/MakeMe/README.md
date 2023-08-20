# What you need
- PCB
- Case
- 18 Kailh hot swap sockets
- 18 Choc v2 low profile switches
- 10 MX keycaps
- 8 MX buttoncaps
- Raspberry Pi Pico (or clone board with same pinout/form factor)
- USB cable
- M3 screws (10mm for through, 6mm for heatset)
- M3 nuts (through hole case)
- M3 heatset inserts (heatset case)

Do the following in order to keep from having to disassemble partway through

# PCB
- Order board (drop the GBR.zip file into the PCB manufacture of your choice. I use JLCPCB)
- Solder sockets onto the back of the board
- Solder pico to the front of the board
- Insert your keyswitches
- Put on your key/button caps

# Firmware
- Hold the Bootsel button on your Pico until it is loaded. 
- Drop the "flash_nuke.uf2" file from the resources folder in the Arkey github onto your pico.
- Wait for it to fully reboot and open as a drive again.
- Drop the ArkeyV2.uf2 file onto the pico.
- Wait for the reboot.

# Case
- Print bottom plate
- Print either the through hole or heatset insert top plate (your choice)

# Assembly
- Place PCB onto bottom plate, it only goes on one way.

### Through hole assembly
- Place the top plate over the PCB and bottom plate.
- Place your nuts in the sunken holes on the top plate
- Screw M3 screws through the mounting holes on the bottom plate up and into the nuts on top
- Screw snug but don't overtighten

### Heatset assembly
- Use your heating tool (I use a soldering iron and 20mm M3 screw) to gently press the inserts into the mounting holes
- Make sure they are alighned correctly using a longer screw. Check that the screw is straight up and down
- Place the top plate over the PCB and bottom plate
- Screw the M3 screws through the bottom plate. Do not over tighten. It should fit snug. 

