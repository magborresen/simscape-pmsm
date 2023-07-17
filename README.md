# SimScape PMSM
This repository contains files for a SimScape implementation for a Permanent Magnet Synchronous Motor (PMSM) with inter-turn fault injection. The model was created based on the mathematical model described in [Interior Permanent Magnet Synchronous Motor Stator Winding Fault Modelling](URL "https://www.sciencedirect.com/science/article/pii/S2405896315008307"). 

## Known Issues
The model does not do well in complex environments. I have tested it with a proprietary sensorless FOC setup in Simulink, but the equations do not converge. One possible reason may be ill-conditioned matrices for the inductance calculations.

The model is also only suitable when modeling motors with 1 pole pair.

## Further Reading
