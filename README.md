# AIM-65-FRAM

Nonvolatile FRAM memory replacement for 2332 ROM used by the Rockwell AIM-65.

This board plugs into any of the 5 2332 AIM-65 ROM sockets. 
A lead to the 6502 R/W signal is needed for writing to the FRAM.

A Write Protect switch allows disconnecting the R/W signal so that the FRAM truly behaves like a ROM.

The FRAM is 8KB, and the 2332 is only 4KB. A switch selected whether A12 is pulled high or low, giving 2 banks of 4KB. 
A12 may also be tied to an I/O pin, such as from one of the 6522s, to allow programmatic bank selection.

