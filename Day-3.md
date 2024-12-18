# Key Learnings
## Design of Power Amplifiers
- 1dB compression point
- Linearity: Ability to reproduce input signal
- Intercept points
- Classes of operation: A,AB,B,C,D,E,F ...
- Different types of devices: Si, GaAs, GaN, SiC
- GaN is preferred over other materials due to various reasons
## Design of PA small signal
- A capacitor is used to block DC component
- Examples: PA (single tone)
- Cadence getting started
- Cadence online support
- First we designed a simple circuit, then we added resistors and a stub to increases stability, the graph seemed to be more stabilized
- There seems to be a tradeoff between gain and stability, and there are other parameters too
- We viewed graphs in logarithmic scale for better understanding of frequency sweep
- We tried out different parameters: NF (noise figure), power, gain, nonlinearity
- Concept of annotations: we can view V and I on every path, node etc.
- With tracing value option, it gets even better, everytime we move the sliding bar, we can note the changes in the V and I on every branch and node.
- Visualization of harmonics in non-linear devices
- Power option in ports, driving the power gives change in the gain and stability graphs
- After adding resitors, we added some inductors and tried out a new configuration
- Then, we matched the input port using `ltuner` by adding conjugate values to this block
- We tried magnitude and angle in measurements tab
