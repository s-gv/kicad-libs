KiCAD Libraries
===============

Some components for which I created custom kicad lib parts.

Schematic Parts
===============

TI
--

- TS3A4751
- MAX4594, MAX4597
- TS3A4742DGK
- REF3312, REF3318, REF3325
- TPL0501-100
- TLV3202
- OPA2314
- ADS1294
- LMP7702

Custom
------

- 2 pin power connector - Note: For footprint, use pin_array_2x1 (pad dia 1.6mm, hole size 1.05mm). DO NOT use SIL-2 which is too small
- 3 pin UART connector - Note: For footprint, use pin_array_3x1 (pad dia 1.6mm, hole size 1.05mm). DO NOT use SIL-3 which is too small
- CC2540 Bluegiga Breakout
- CCDebugger port
- ML506 Virtex-5 Board header(HDR1)
- 3 pin ECG probe (SMD)
- Ring type ECG electrode (ECGANT)

Footprints
==========

Custom
-------

- 30 pin CC2540 bluegiga breakout board
- 10 pin CCDebugger
- ML506 Virtex-5 Board header(HDR1)
- 10 pin 1 row connector(PIN_ARRAY_10x1)
- Ring type ECG electrode (ECGANT)

Notes to myself
--------------

To create a new library part, do these. (Similar steps for creating footprints)

- Open EESchema
- Open Library editor (a few buttons to the left of annotation tool with a pen in the icon)
- Create new part
- Create the part
- Select working library/save part to new lib
- Save part to lib

Online quick generators

- Lib: http://kicad.rohrbacher.net/quicklib.php
- Footprint: http://kicad.rohrbacher.net/quickmod.php

