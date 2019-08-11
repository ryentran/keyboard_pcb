# Keyboard PCB Design
This is a keyboard design for a 3x3 macropad created using KiCAD, Hasu's keyboard_parts [component library](https://github.com/tmk/kicad_lib_tmk) and [footprint library](https://github.com/tmk/keyboard_parts.pretty), and /u/techieee's [switch footprint library](https://github.com/egladman/keebs.pretty).

# Schematic
<img src = "3x3%20macropad%20v1/images/3x3%20macropad%20v1%20Schematic.jpg" width = "1000">

# PCB
<img src = "3x3%20macropad%20v1/images/3x3%20macropad%20v1%20PCB.jpg" width = "300">

After creating the schematic and pcb design for the macropad, the pcb was printed using prototyping services ([JLCPCB](https://jlcpcb.com/)). Once the pcb was received, SMD components were handsoldered to the board and tested for functionaility. THE MCU used for this project is an atmega32u4 which was programmed with a hexfile generated by [QMK_firmware](https://github.com/qmk/qmk_firmware).
