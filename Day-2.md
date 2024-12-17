# Day-2 Key Learnings (All the circuits and schematics were realized using AWR)
- Lumped to Distributed theory (components at low frequency v/s at higher freq)
- Read about s-parameters
- Why use s? Can cascade s-parameters of multiple devices to predict system performances, can compute H,Y or Z parameters form s-parameters if desired, relate to familiar measurements( gain, loss, reflection coefft)
- Smith Chart maps rectilinear impedance plane onto polar plane.
## Matching N/W design
> - Conjugat design
> - Negative Image design
> - Optimum load line for power devices
- Narrowband-> 20% of center freq
- Wideband-> > 30% (defense purposes: Electronic Warfare(EW), 2-10GHz)
## Impedance Matching N/W
> - Low freq: lump elements
> - Medium freq: Semi-lump
> - High: distributed
- RF uses 4 to 6 layer PCBs: Why do you need more layers?
# Recommended Reading
> - "Reviewing the basics of microstrip lines" by Leo. G. Maloratsky
- Read about propagation modes
- Choosing the dielectric materials is very important: substrates made of different materials
- Higher dielectric leads to small size antenna but higher losses (loss tangent)
- Calculation of effective dielectric
- FR-4 material is used for Green color PCBs (two layer)
## Microstrip line circuit model
> - High impedance line is shaped into loops to get inductor behavior.
> - Spiral tracks have more inductance
## Types of Simulators
> - Linear: Passive N/W
> - Harmonic balance: Medium non-linearities, multitone analysis, high freq
> - SPICE: good for strong non-linearities, low freq
> - Envelope: Represents modulated waveforms with complex envelope
> - 2.5D EM: Microstrip, RFICs, multilayer PCBs, thin printed Antennas
> - 3D EM: packages, wirebones, waveguides, FEM/FDTD
- Touchstone file format: *.Snp where n is the no. of ports
- Noise data is very important, only then you can do LNA design (Low noise amplifier)
- What are linear models, non-linear models (curtice, angelov, TOM), proprietary models.
- Different classes of EM Simulators: cross sectional solvers, method of moments, FEM/FDTD
- 90 degrees corresponds to lambda/4, 180-> lambda/2
- Electric length changes the physical length of the Microstrip line
- Learn all the frequency bands
- Teflon has dielectric constant of 2.2
- mil = 1/1000 th of an inch
- W/H should not be comparable, meaning the thickness of the dielectric and the thickness of the metal sheet shouldn't be same.
- Wilkinson's power divider circuit to be learnt
- Linear v/s Non linear devices
## What is Low Noise Amplifier (LNA)
> - increases desired signal amplitude without distortion or noise
> - determines noise figure
- Frii's formula for noise figure
- RF amplifier design flow
- Device stability concept
