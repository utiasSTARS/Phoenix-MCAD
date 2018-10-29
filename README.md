# Hummingbird-MCAD
This respository contains all the mechanical design documents and a bill of materials (BOM) for construction of a Hummingbird Tailsitter.

## BOM

A Live BOM of all the off-the-shelf documents currently used in the Hummingbird project to construct one unit of the vehicle is provided [here](https://docs.google.com/spreadsheets/d/1CfngokLHG-t1se26QiAbY0H6btnje3BByeZrX1zNAr0/edit?usp=sharing).

## Overall STEP File
[This STEP file](./Hummingbird_V3_MECH.STEP) contains the CAD design of the overall vehicle, defining the shape of the wing and the interconnection mechanism between wings, mounting plate, landing gears, etc. Import this STEP file into any preferred CAD software to inspect the shape and dimensions in detail, or to modify the design to suit specific needs.

## 3D printing STL Files
We also provide default CAD model (.stl) files which are ready to be 3D printed. This allows you to directly print all the necessary components needed for assembly without modifying the CAD design. These files are located in the subfolders of this repository.

## Wing Core Casting
To make a rigid (crash-proof) yet light wing, we decided to use 2lb/cu-ft. polyurahene foam for casting the wing core. The procedure is as follows: 
- Print out the 3D-printed molds in the **WingCore_Mold** folder (due to the volume constraint of our printer, the mold is divided into four parts and joined together by **Align_Pins**)
- Apply a thin layer of body filler (such as epoxy or bondo) to fill the gaps between filament layers
- Sand the surface to be as smooth as possible until the surface is almost reflective
- Apply one layer of mold release (extremely important!) over the mold (including the flash surface)
- Mix an appropriate amount of foam and follow the casting instructions of your foam (we use 20ml of component A and B each for one side of the wing core)
