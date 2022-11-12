# DSO138 Oscilloscope

This is the JYE Tech DSO128 Oscilloscope put behind a 10 cm wide Kosmo format panel. 

Slide switches and tactile buttons are mounted to an auxiliary PCB. BNC input connects to this board and from there to scope board. 1/4" input jack connects to this board, with signal going through an op amp buffer and from there out to scope input and to 1/4" through jack.

LED is mounted to aux board and feeds through panel hole. Or maybe shine through panel?

Maybe use ribbon cables and IDC headers to link scope board to aux board. (8 wires needed for each DP3T switch; 8 wires needed for 5 tact buttons + input + LED (a, k). So 4 8-pin IDC headers.) Also JST headers to connect jacks and toggle.

Eurorack header on aux board provides power for op amp and (via wire to power connector) scope.

BNC connects directly (on panel) to one throw of a SPDT toggle switch, center switch terminal via aux board to DSO input. Audio jack is buffered and op amp output connects to other throw of toggle switch. Audio jack also buffered and connects via 1k to through jack.

## Aux board to panel:

### JST:

* Input switch
* Audio jack for buffer to through
* Through jack

## Aux board to scope PCB:

### 8 pos IDC:

* DP3T switches (x3)
* 5 tactiles + ground + input + LED

### JST:

* Power

Parts:

|Qty|Desc|Part #|Vendor|SKU|
|----|----|----|----|----|
|3| DP3T slide switch |OS203012MU5QP1|Digi-key||
|5| Tact button |TL1100F160Q|Digi-key||
|4| Tact button cap, black |4JBLK|Digi-key|EG1080-ND|
|1| Tact button cap, red |4JRED|Digi-key|EG1078-ND|
|1| SPDT toggle switch ||Tayda||
|1| BNC jack |1-1337541-0|Digi-key|A97557-ND|
|2| 1/4" audio jack||Tayda||
|1| 5mm LED, green ||Tayda||
|4| Shrouded 2x4 pin header ||Tayda||
|4| 2x4 IDC connector ||Tayda||
|2'| 8 conductor ribbon cable ||Tayda||
|1 | 6" 40 conductor male/female IDC ribbon cable assembly |H3AKH-4006G|Digi-key|H3AKH-4006G-ND|
|1| Shrouded 2x5 pin header ||Tayda||
|3| Molex 2 pin header ||Tayda||
|3| Molex 2 pin connector ||Tayda||
|6| Molex crimp ||Tayda||
|1| JST 2 pin connector |XHP-2|Digi-key|455-2266-ND|
|2| JST crimp |SXH-001T-P0.6N|Digi-key|455-4220-1-ND|
|1| TL072 op amp ||Tayda||
|1| 1M resistor ||Tayda||
|1| 1k resistor ||Tayda||
|2| 10 uF electrolytic cap ||Tayda||
|2| 100 nF ceramic cap ||Tayda||
|2| 1N5817 Schottky diode ||Tayda||

