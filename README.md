# BLUE

## This is a Build Log for my Voron Trident 300 mm DIY 3D Printer called "Blue":

Primary Color: 3dPrintLife Black
Accent Color: 3dPrintLive Blue

## Kit

* [Formbot VORON Trident CoreXY 3D Printer Kit](https://www.formbot3d.com/products/voron-trident-corexy-3d-printer-kit-with-premade-wiring-harness)
  Dragon Standard Flow Hotend Upgrade
* [Stealthburner Extruder Upgrade Kit for Voron 2.4 or Trident](https://www.formbot3d.com/products/-176)
  I know its standard now, but my kit came with parts required for Afterburner.
* [PIF parts printed by wsebastian](https://pif.voron.dev/)

## Issues

1. Magnetic Sheet for Bed
    * When I pulled the paper backing off it pulled the glue off the magnet as well.
    * Purchased [Magnetic Flex Plate Double-Sided and Single-Sided with 3M Magnetic Backing (Energetic & West3D Collab)](https://west3d.com/products/double-sided-texture-smooth-flex-plate-with-3m-magnetic-backing-energetic-west3d-collab)
    * It said 3M on the back. Must have been more like 1.5M.
2. LEDs in Stealthburner Kit
    * My research says they are RGB but the colors are not correct. I have tried the other options in the config file. Still wrong colors.
    * I'm leaving it as it is for now. I don't really care about the colors.
    
## Process

I currently have a working printer. I still have the following to do to get it ready for serial.

1. Cosmetic Parts
    * ~~Wire Covers (stock STL) PRINTED NEED TO INSTALL~~
    * ~~Acrylic Panel Latches PRINTED NEED TO INSTALL~~
      * ~~Using [these](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/richardjm/snap-latch-2020) to hold the panels on. 3.5mm for the clear and 4.0mm for the back panel.~~
    * Exhaust Cover
      * ~~Don't want to have the normal filter on the back. At some point I'll print a Nevermore Filter. So the goal is to seal up the back for now.~~
      * ~~Using [this](https://github.com/MotorDynamicsLab/LDOVoronTrident/tree/master/STLs/Angled%20Exhaust%20Cover) cover to fully block the back and give angle for the PTFE tube.~~
      * ~~Using [this](https://github.com/Diyshift/3D-Printer/tree/main/Trident%20Noodle) noodle to adjust the bend of the PTFE tube to not rub against the upper acrylic panel.~~
      * I may need [this](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Galvanic/Bowden_Tube_Guide) to keep the PTFE tube clear. We'll see.
    * Skirts
      * Stock STLs. No mods. PRINTING NEED TO INSTALL
    * Screen
      * Stock STLs. No mods. PRINTED NEED TO INSTALL
    * Bottom Panel
      * Stock STLs. No mods. PRINTED NEED TO INSTALL

2. Mods I want to do
    * [LDO Motors Input Shaper Kit (ADXL)](https://kb-3d.com/store/ldo/655-ldo-motors-input-shaper-kit-1661370490021.html) HAVE IT NEED TO INSTALL/CONFIGURE
    * [Nevermore Micro V5 Duo](https://github.com/nevermore3d/Nevermore_Micro)
    * [Decontaminator](https://github.com/LoganFraser/VoronMods/tree/main/DecontaminatorTrident/STLs)
    * [20x20mm Profile Covers](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/chri.kai.in/20x20mm_Profile_Covers)
    * [Chamber Thermistor](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/samwiseg0/extrusion_thermistor_mount)
    * [Eddie's LED Bar Clips](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/eddie/LED_Bar_Clip)
    * [Bed Fans](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/CannedBass/Trident_Bed_Fans) w/ [Ellis's Macros](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Bed_Fans)
    * ~~[Top corner sealing plug for Voron Trident](https://www.printables.com/model/375617-top-corner-sealing-plug-for-voron-tridentv24)~~
      * Installed (with a hammer)
