# Circuit Design and Implementation

The DAC was implemented using an 8-bit R-2R ladder network
constructed from discrete resistors. Care was taken to
maintain consistent resistor values, as matching between
R and 2R directly affect output accuracy.

Digital inputs were applied using toggle or DIP switches,
allowing manual selection of 8-bit binary values during
testing. This made it easy to observe the effect of each
bit on the output voltage.

An operational amplifier was used at the output stage as a
buffer. Since the R-2R ladder has a relatively high output
impedance, the op-amp helped reduce loading effects and
provided a stable, low-impedance output suitable for
measurement.

The complete circuit was fabricated on a hand-etched PCB.
Manual layout and etching were performed, followed by
component placement and soldering. The design was kept
simple to ensure reliable operation and ease of debugging.

