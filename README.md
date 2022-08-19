# Lick Detector Electro

This is a migration of the [Dual Lick Port](https://www.janelia.org/open-science/dual-lick-port-detector)
from [Janelia Research Campus](https://www.janelia.org/).

## Device Overview

The Dual Lick Port uses a [two-transistor amplifier circuit](https://www.electronics-notes.com/articles/analogue_circuits/transistor/amplifier-npn-pnp-two-transistor-circuit.php)
to detect licks from an instrumented lick port where the mouse receives liquids.
This detection circuit can be operated isolated or non-isolated from the output
signal made available on each Lick Port.

Lick Ports can be plugged directly into a a Harp Behavior Device Port as-is
with a CAT6 cable.

This board also exposes each Lick Port's 12V output via the two Molex Microfit
3 sockets on the top-and-bottom right side of the board.

## Connection Overview
![](./board/pics/dual_lick_port.png)

## Schematic

[schematic.pdf](./board/JF-SV-LP0001.pdf)


