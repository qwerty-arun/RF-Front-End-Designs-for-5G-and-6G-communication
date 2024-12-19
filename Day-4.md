# Day-4 Key Learnings
- We can directly add transistors models manufactured by various companies into the schematic.
- If not available, you need to ask cadence after creating an account
- ACLR: Adjacent Channel Leakage Ratio
- HEMT: High Electron Mobility Transistor
- What are the different types of classes of transistors: A, B, AB etc
- A: high linearity but low efficiency
- B: greater efficiency than A, but high distortion
- AB: combines A and B, efficiency is greater than that of A and has lower distortion than B. Achieved by biasing both transistor so they conduct when the signal is nearly zero (point where B introduces non-linearity).
## Paper Reference
> - "Broadband High Power Amplifier Design Using GaN HEMT Technology" - Turkish paper
> - Goal: 50% power added efficiency
> - Bias Point chosen: Vds=28V, Vgs=-2.1V, Idq=336mA
> - RF Chokes and DC Blocks are used to make the circuit operate at selected bias point while minimizing noise from power lines
- What are RF Chokes? Inductor which is used for frequency selectivity to allow passage of low-freq DC signals while blocking high-freq AC signals
- What are DC Blocks? Coaxial components that prevent flow of audio and direct current frequency while offering min. interfrence to RF signals
- Concept of Load and Source Pull 
