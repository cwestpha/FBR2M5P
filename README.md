
Flying Bear Revolution 2
BTT Manta 5P Swap
By cwestpha/Athirne


Why?
Ideally I want to make this as modular as possible. Everything user definable to customizable goes in thie printer.cfg file.
Generated variables through system tuning, meshing, etc are all stored in seperate files.
Everything else is optional tweaks or upstream things you can pull and use plug n prey style. Comment out what you dont have...
Do sanity check things and make sure you go through the basic checks to validate everything is plugged in and works
before your first major move/print/etc.

What is mantatory for this?
I suggest setting up with Kiauh. Then you will need to go through pulling in the jschuh klipper macros. 

-What I pulled from upstream to make this-
Based on https://github.com/bigtreetech/Manta-M5P for original config
remapping guidence/leads from Aurora Tech's video https://www.youtube.com/watch?v=ERMAXpD7mM8&t=769s&pp=ygUcZmx5aW5nIGJlYXIgcmVib3JuIDIga2xpcHBlcg%3D%3D
the awsome macros from https://github.com/jschuh/klipper-macros

-KAMP module-
https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging


-Microprobe Module-
https://github.com/bigtreetech/MicroProbe
&


-Revo Stealthburner + CAN + Galileo 2 Module-


-Voron Tap Module-
REQUIRES Stealthburner above
REQUIRES Y-axis rebuild mod
CONFLICTS Microprobe


-Chamber Control Module + Nevermore-


-Filiment Sensor + feed tracker Module-
