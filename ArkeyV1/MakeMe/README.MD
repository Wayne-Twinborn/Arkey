# Parts you need:
- Raspbery Pi Pico with soldered headers
- Keyboard MX 5 style pin key switches: https://www.amazon.com/gp/product/B09314WK5Z
- 10 MX style keycaps to fit the switches
- 8 22mm button caps to fit the right half: https://www.amazon.com/dp/B0BKDBFBMP
- Micro USB cable
- The PCB (import the easyeda file into easyeda and order it through jlcpcb)
- The case (optional, local or use SendCutSend)
- Rubber feet (optional if not using case): https://www.amazon.com/gp/product/B07CNQC695	
- Size 6 machine bolts 1" long (optional, only for case)

# Assembly
## Board
- Solder key switches
- Solder Pico with USB facing to the right

## Case
### Acrylic
- Plate order is Bottom > PCB > Middle > Top
- Use the rubber feet on the bottom of the PCB to provide spacing from the bottom plate
- Size 6 machine bolts. Length depends on how you want to cap them. Take it to the hardware store. 
- For the art, you can print it on standard 8.5x11 paper without issue. Be aware that the template markings are smaller than  the actual cut out in order to prevent an outline being visible. 
  
### 3D Print
- Whole panels
- Print the 2 panels in the folder
- Push size 6 machine screws through the bottom plate going up, pushing them into the counterbore holes.
- Optionally cover the screw heads with rubber feet
- Place the PCB on the 4 bolts on top of the plate with the 3 support posts in a row on the right side.
- Feed your USB solution through the hole (If you're going to use a panel mount option, make sure you stick the cable to the top plate so it doesn't interfere with buttons)
- Place the top plate over the 4 bolts until they poke up.
- Apply the nut of your choice. I like cap nuts myself

- Split Panels
- If you can, print the bottom panel whole from the whole panels folder. It's worth it to use the extra time and filament to print at an angle with support and get that panel whole.
- If you have a whole bottom panel, print the top left and top right panels.
- Fit the 2 halves together. Depending on your filament, print settings, printer, etc you may need to do some sanding to make them fit snug. 
- If you don't have a whole bottom, print the bottom halves and fit them together.
- Follow the steps after printing in the whole panel section.


- For whole panels, use size 6 machine bolts through the bottom panel, push to force them into the counterbore holes. Slide the pcb onto the bolts on top (the 3 support pillars go on the right)

## Firmware
### Custom config method
- Hold the bootsel button on your Pico and plug it into your PC, it will be recognized as a USB drive.
- Drop Arkey.uf2 onto the Pico. 
- It will reboot on its own and you should have a working controller.
- Hold the leftmost button on the top row while plugging in to get into webconfig if you want to change settings. 

### Official direct method
- If you want to do it manually, you can obtain the firmware direct from the community and configure it manually.
- Get the firmware you need at https://gp2040-ce.info/ and follow their instructions to install it.
- Hold the rightmost button on the top row while plugging in the controller to access the web config.
- Under Configuration > Data Backup and Restoration, import the Backup.gp2040 backup file.
- Click the Reboot button and you should have a working controller.
- The leftmost button will now be S2 and be used to get into the web config. 

# Button Layout
From left to right on the top row
- Start
- Select 
- Home
- L3
- R3
- Screenshot

Buttons are standard layout for a modern stick. 
Top button row from left to right
- Square/X
- Triangle/Y
- R1/RB
- L1/LB

Bottom row
- X/A
- Circle/B
- R2/RT
- L2/LT


# Buttons
You can find compatible 3d printable caps at https://github.com/sgfdevices/Bridget/tree/main/Buttons
