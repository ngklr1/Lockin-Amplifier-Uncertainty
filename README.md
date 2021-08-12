# Lockin-Amplifier-Uncertainty

The purpose of this notebook is to characterize uncertainty and noise associated with a lockin amplifier measurement.

Lockin amplifier: A tired EG&G Princeton Applied Research Model 5210 Lock-in Amplifier purchased on ebay.

Four probe resistance measurement: The circuit consisted of the lockin amplifier internal oscillator, a 1 kOhm current limiter,
an 0.5 Ohm sample, and ground. Resistor boxes with BNC connectors were constructed, and connections were made by
coaxial cable. Measurement of the sample resistor was performed in A-B mode of the lockin amplifier. Measurements are
displayed as voltages except for the internal oscillator voltage sweep where the voltage measurement was converted
to resistance.

Questions
    What is the optimal internal oscillator voltage based on the uncertainty profile?
    What is the optimal internal oscillator frequency based on the noise profile?
    What is the optimal time constant based on the uncertainty profile?
    How does uncertainty evolve in time with a repeated measurement?
    Can uncertainty be determined by sweeping through a full cycle of the phasor offset angle?

