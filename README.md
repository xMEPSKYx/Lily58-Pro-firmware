# Lily58-Pro-firmware
Precompiled firmware for Lily58 Pro split keyboard.

Here you can find precompiled firmware for Lily58 for both VIA and VIAL.


In order to flash new firmware please do following:


1. Unplug USB-C cable from the keyboard.

2. Unplug TRRS cable.

3. Plug in USB-C cable to one of the halves.

4. Press reset button (next to Pro Micro) twice, microcontroller should show up in your system as new removable drive named RPI-RP2. Some linux distros may need to manually mount the drive.

5. Drag and drop the uf2 file onto this RPI-RP2. It should automatically disconnect and then connect as a keyboard.

6. Repeat 4 and 5 with another half.

7. Unplug USB-C, connect two halves with TRRS again, plug USB-C. By default left half is set as master.
