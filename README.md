# Prusa i3 MK2 Firmware for RAMPS 1.4
This firmware was forked from prusa3d/Prusa-Firmware git repository and modifed to work on RAMPS 1.4 board + Gadget 3D LCD.
A few bed, pinda, and stepper constants and offsets were also modifed to support my DIY clone of the Prusa i3 design.

Mechanical changes:
- 220 x 220 bed
- MK3S hotend pinda offset
- 3/4" plywood frame
- RAMPS 1.4 + A4988 drivers


## General instructions

Clone this repository
Connect computer to RAMPS board via USB
Use Arduino 1.0.6 to compile and flash

## Build instructions

### Step 1

Install Arduino 1.0.6

### Step 2

Remove Liquid Crystal library from your arduino or rename it

### Step 3 

Install the arduino addon located in the root of this repo. Don't forget to install correct version!

### Step 4 (Optional)

Copy the configuration file matching your printer from variants folder to the the Firmware folder

### Step 5 (Optional)

Rename it to "Configuration_prusa.h"

### Step 6

Compile the firmware

### Step 7

Upload the firmware to board





