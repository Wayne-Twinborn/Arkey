# Parts you need:
-	Raspbery Pi Pico with soldered headers
-	Keyboard MX 5 style pin key switches: https://www.amazon.com/gp/product/B09314WK5Z
-	10 Keyboard caps to fit the switches
-	8 22mm button caps to fit the right half: https://www.amazon.com/dp/B0BKDBFBMP
-	Micro USB cable
-	The PCB (import the easyeda file into easyeda and order it through jlcpcb)
-	The case (optional, local or use SendCutSend)
-	Rubber feet (optional if not using case): https://www.amazon.com/gp/product/B07CNQC695	
-	Size 6 machine bolts 1" long (optional, only for case)

# Assembly
- Assembly is pretty easy. Solder all the key switches into place, solder the Pico to the board, put it in the case if you have it (case steps at the bottom), put all the caps on the switches, and configure it.
- Get the firmware you need at https://gp2040-ce.info/ and follow their instructions to install it.

You'll need to reconfigure the pin layout. To get to the web config, hold down the 6 key (farthest to the right in the function row) and plug it in.
Follow the instructions at the gp2040-ce site to import the backup file. 

Once you've done that you're ready to rock. Feel free to configure whatever you want. The pin layout is as follows. 

0: L2
1: R2
2: Circle/B
3: X/A
4: L1
5: R1
6: /\  / Y
7: [] / X
8: 1 (start)
9: 2 (select)
10: 3 (home) 
11: 4 (Left Stick)
12: 5 (Right Stick)
16: D/Right
17: 6 (for web config) / Capture
18: W/Up
19: S/Down
20: A/Left

An art template is included. It is set for letter size printing so grab your average paper and go. It does need trimming that you'll need to do once you have case in hand.


# Case
For the case to fit without bothering your solder points, you'll want to use rubber feet. You'll want to place them at the corners and in empty spaces on the bottom of the PCB. They'll be between it and the bottom plate. 
This will give the case a pressure fit that holds the board in place well while giving space for the electronics.