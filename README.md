# HST-lighting-upgrade-board

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/02b5c512db344d83841de876ed6c7de5)](https://app.codacy.com/app/berry120/HST-lighting-upgrade-board?utm_source=github.com&utm_medium=referral&utm_content=berry120/HST-lighting-upgrade-board&utm_campaign=Badge_Grade_Dashboard)

A PCB allowing the lighting to be upgraded from the standard bulb - fits the old Hornby/Lima class 43 (Intercity 125) with the ringfield motor.

Distributed as an Eagle project.

For analogue operation, ignore PAD3 (DCC common) at the bottom, and solder wires from each rail to the two pads at the top.

For DCC operation, assuming standard wiring conventions, connect the blue wire to DCC common, the white wire to the left hand pad at the top, and the yellow wire to the right hand pad at the top.

![Schematic](schematic.png)