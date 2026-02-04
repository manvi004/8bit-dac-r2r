# Theory of the R-2R Ladder DAC

An R-2R ladder DAC is a commonly used digital-to-analog conversion technique that relies on a repetitive structure of only two resistor values, R and 2R. This makes the design simple, scalable, and practical for hardware implementation.

Each bit of the digital input controls a switch that connects
either to the reference voltage or to ground. The ladder
network divides the voltage in such a way that each bit
contributes a weighted portion of the final output.

For an N-bit DAC, the ideal output voltage is given by:

Vout = Vref × (Digital Value / 2ⁿ)

In the case of an 8-bit DAC, this results in 256 discrete
voltage levels between 0 V and the reference voltage. The
smallest change in output voltage (resolution) is therefore
Vref / 256.

The R-2R ladder architecture is preferred over weighted
resistor DACs because it requires fewer unique resistor
values and offers better matching characteristics.
