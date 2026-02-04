# 8-bit Digital-to-Analog Converter (R-2R Ladder)

## Overview
An 8-bit Digital-to-Analog Converter (DAC) designed and implemented using an R-2R ladder network.
The project converts digital input values into proportional analog output voltages.

The DAC was physically implemented on a hand-etched PCB and tested for linearity and accuracy.

## Working Principle

An R-2R ladder DAC operates using only two resistor values, R and 2R,
arranged in a repeating ladder structure. Each bit of the digital
input contributes a weighted portion of the reference voltage, and
the combined effect produces a continuous analog output.

For an ideal 8-bit DAC, the output voltage follows the relation:

Vout = Vref × (Digital Value / 256)

This results in 256 discrete voltage levels between ground and the
reference voltage.

## Circuit Implementation

The DAC was implemented using discrete resistors configured in an
8-bit R-2R ladder network. Toggle/DIP switches were used to manually
apply digital input values during testing.

An operational amplifier was included at the output stage as a
buffer to reduce loading effects and improve output stability. The
entire circuit was fabricated on a hand-etched PCB, with careful
attention to layout and connectivity.

## Testing and Results

The output voltage was measured for various digital input
combinations using a digital voltage display and a multimeter. The
measured output showed a step-wise and approximately linear change
with respect to the applied digital input.

Minor deviations from ideal values were observed, primarily due to
resistor tolerance and manual fabrication limitations. Overall, the
behavior closely matched the theoretical expectations of an R-2R
ladder DAC.

## Tools and Skills Applied

1. Analog circuit design and analysis
2. PCB Designing and etching
3. Hardware testing and measurement
4. Troubleshooting and problem solving  

## Note

This project was completed as part of undergraduate coursework and emphasizes hands-on hardware implementation and validation.
