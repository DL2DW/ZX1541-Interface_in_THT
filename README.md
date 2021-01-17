# ZX1541 Interface in THT



![](https://github.com/DL2DW/ZX1541-Interface_in_THT/blob/main/Images/ZX1541-Interface_in_THT.jpg)



I had already presented this interface here, but in a version with SMD components. Since many do not like to solder SMD, I have created the interface again, but this time completely in conventional through-hole assembly.

Otherwise, everything I said about the SMD version of the interface applies, except of course the parts list.






## Assembly

The interface is very densely packed. But should still be very good to solder even for beginners.

Except for the RAM component, everything is very easy to reach. Since this interface should also find space in the housing of an old 16K memory expansion, the space was of course limited.

Therefore I placed the RAM below the EPROM. Furthermore I chose the narrow version with 7.62mm width.

The RAM component must also be soldered unfortunately, because there is no more place for a socket.

Here once in the 3D view, how the RAM is installed:

![](https://github.com/DL2DW/ZX1541-Interface_in_THT/blob/main/Images/ZX1541-Interface_in_THT_PCB_3D_RAM.jpg)



To use the EPROM now, it must of course be installed in a raised position. For this you either take an IC socket and cut it accordingly. Or socket strips are used. 

The RAM should be soldered first. Then insert the EPROM into the cut IC socket or socket connectors and solder it in. So you don't have the problem later that the EPROM could not fit.

Apart from that there is nothing else to consider.



![](https://github.com/DL2DW/ZX1541-Interface_in_THT/blob/main/Images/ZX1541-Interface_in_THT_PCB_3D.jpg)



## BOM

Here is the list of components needed. I have chosen the manufacturers as examples. Of course, compatible components from other manufacturers can also be selected.

| Designator                     | Quantity | Manufacturer 1      | Manufacturer  Part Number 1 | Description                                                  |
| ------------------------------ | -------- | ------------------- | --------------------------- | ------------------------------------------------------------ |
| U8                             | 1        | Texas  Instruments  | SN74LS174N                  | Flip  Flop D-Type Bus Interface Pos-Edge 1-Element 16-Pin PDIP Tube |
| U7                             | 1        | Texas  Instruments  | SN74LS32N                   | Texas  Instruments SN74LS32N, Quad 2-Input OR Logic Gate, 4.75 5.25 V, 14-Pin PDIP |
| U6                             | 1        | Texas  Instruments  | SN74LS06N                   | IC  INVERTER OPEN COL 6CH 14DIP                              |
| U5                             | 1        | Texas  Instruments  | SN74LS365AN                 | Buffer/Line  Driver 6-CH Non-Inverting 3-ST Bipolar 16-Pin PDIP Tube |
| U4                             | 1        | Texas  Instruments  | SN74LS139AN                 | TEXAS  INSTRUMENTS     SN74LS139AN      IC, DECODER/DEMUX, 74LS139 |
| U3                             | 1        | Texas  Instruments  | SN74LS08N                   | IC  GATE AND 4CH 2-INP 14DIP                                 |
| U2                             | 1        | Microchip  / Atmel  | AT28C64B-15PC               | IC  EEPROM 64KBIT 150NS 28DIP                                |
| U1                             | 1        | Hitachi             | HM62256BLSP7                | Contact  for details                                         |
| R16                            | 1        | Yageo               | CFR-25JB-52-33K             | RES  33K OHM 1/4W 5% AXIAL                                   |
| R12                            | 1        | Yageo               | CFR-25JB-52-4K7             | RES  4.7K OHM 1/4W 5% AXIAL                                  |
| R6, R15                        | 2        | Yageo               | CFR-25JB-52-680K            | Res  680K Ohm 1/4W 5% Axial                                  |
| R5, R8, R9, R10, R11, R13, R14 | 7        | Yageo               | CFR-25JB-52-1K              | RES  1K OHM 1/4W 5% AXIAL                                    |
| R3                             | 1        | Yageo               | CFR-25JB-52-10K             | RES  10K OHM 1/4W 5% AXIAL                                   |
| Q3                             | 1        | Diotec              | BC557C                      | Trans  GP BJT PNP 45V 0.1A Automotive 3-Pin TO-92 T/R        |
| Q1, Q2                         | 2        | NTE  Electronics    | NTE2355                     | PRE-BIASED  DIG TRANSISTOR, 50V, TO-92; Transistor Polarity:NPN; Collector Emitter  Voltage V(br)ceo:50V; Transition Frequency ft:250MHz; Power Dissipation  Pd:300mW; DC Collector Current:100mA; DC Current Gain hFE:50; No. of Pins:3  ;RoHS Compliant: Yes |
| D10                            | 1        | Wurth  Electronics  | 151033GS03000               | WURTH  ELEKTRONIK - 151033GS03000 - LED, Green, T-1 (3mm), 530 nm, 3.2 V, 30 mA, 15  cd RoHS Compliant: Yes |
| D5                             | 1        | Wurth  Electronics  | 151033RS03000               | WURTH  ELEKTRONIK  151033RS03000  LED, 3MM,   RED, 2600MCD, 621NM |
| D1, D2, D3, D4, D6, D7, D8, D9 | 8        | NXP  Semiconductors | 1N4148                      | NEXPERIA  - 1N4148 - DIODE, 1N4148 AMMO-BOX 10K              |
| CN3                            | 1        | Samtec              | TMM-105-03-S-S              | Conn  Unshrouded Header HDR 5 POS 2mm Solder ST Thru-Hole Automotive Bulk |
| CN2                            | 1        | Sullins             | PRPC002SFAN-RC              | CONN  HEADER .100" SNGL STR 2POS                             |
| CN1                            | 1        |                     |                             | Sinclair  Edge Card Connector                                |
| C9                             | 1        | KEMET               | C315C105K3R5TA              | Multilayer  Ceramic Capacitors MLCC - Leaded 25volts 1uF 10% X7R |
| C1, C2, C3, C4, C5, C6, C7, C8 | 8        |                     |                             | Ceramic  Disc Capacitors 100nF -20%~+80% 50V Through Hole,P=2.54mm RoHS |



If you liked my project, I would be very happy about a small coffee donation.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R62T6RN)



# License

The contents of this repository, with the exception of the files_found_on_the_internet and Firmware directories, are released under the following license:

- the "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License" (CC BY-NC-SA 4.0) full text of this license is included in the [LICENSE.CC-NC-BY-SA-4.0](https://github.com/DL2DW/ZX1541-Interface_in_THT/blob/main/LICENSE.CC-NC-BY-SA) file and a copy can also be found at https://creativecommons.org/licenses/by-nc-sa/4.0/
