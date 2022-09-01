# Universal-Teensy-4.0-Eurorack-Shield
This PCB is designed to piggyback onto a perfboard, to eneable easy designing and building of custom DSP based eurorack modules. One could say it's a eurorack Module-Module. It features two 24-bit audio input and two 24-bit audio output channels. The corresponding DAC and ADC are wired up to easily work with the PJRC audio library. 

## Components
All components minus the Teensy 4.0 microcontroller and PCB can be easily ordered with the mouser project below
https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=7126760366

The PCB can be ordered at a PCB manufacturer of your choice. I ordered mine at Aisler.

## Building Notes
I recommend to reflow solder this board, since most pads are really close to eachother. If you however choose to handsolder, my advice is to go from smallest to largest component.

The headers on the teensy need to be on the same side as the USB port, so that the USB port faces towards the PCB when mounted. This is done to allow utilisation of the backside pins of the Teensy. There are also 5V and GND markings on the PCB to ensure correct orientation.

## Schematic
<img src="/Images/Schematic.png" alt="Schematic" title="Schematic.png">

## 3DRender
<img src="/Images/3DRender.png" alt="3DRenderg" title="3DRender.png" height="600">

## Example Modules
There are currently no working examples. I am however working on a wavetable module based on this board. I'll add it as soon as it's finished.

## Disclaimer
This design wasn't yet tested in an eurorack environment. Everything ***should*** work as intenden and be +-12V tolerant, if hooked up like in the schematic, but this has yet to be verified.
