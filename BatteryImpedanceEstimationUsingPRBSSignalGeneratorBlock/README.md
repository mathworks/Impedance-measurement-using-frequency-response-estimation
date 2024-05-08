# Estimate Battery Impedance Using Signal Generator Blocks

This example shows how to use frequency response estimation to estimate the impedance of a battery modeled using Simscape™ Battery™ software. To generate a perturbation signal for frequency response estimation (FRE),
you can use the signal generation blocks from Simulink® Control Design™ software. You can use the [PRBS Signal Generator block](https://www.mathworks.com/help/slcontrol/ug/prbssignalgenerator.html) to generate PRBS perturbation signals,
which provide fast estimation in power electronic applications. This example also shows how to process the experiment data by using a data logging block and the [frestimate](https://www.mathworks.com/help/slcontrol/ug/frestimate.html) 
function to derive the battery cell impedance. To examine the impedance measurement, you can compare against a transfer function from manual derivation.


## Setup
Run the livescript 'BatteryImpedanceEstimationUsingPRBSSignalGeneratorBlock.mlx'. Ensure you have the necessary MATLAB&reg; toolboxes installed (mentioned below).


### MathWorks Products (https://www.mathworks.com)

Requires MATLAB release R2024a or newer
- [Simulink&reg;](https://www.mathworks.com/products/simulink.html)
- [Simscape&trade;](https://www.mathworks.com/products/simscape.html)
- [Simscape&trade; Electrical&trade;](https://www.mathworks.com/products/simscape-electrical.html)
- [Simscape&trade; Battery&trade;](https://www.mathworks.com/products/simscape-battery.html)
- [Control System Toolbox&trade;](https://www.mathworks.com/products/control.html)
- [Simulink&reg; Control Design&trade;](https://www.mathworks.com/products/simcontrol.html)
- [System Identification Toolbox&trade;](https://www.mathworks.com/products/sysid.html)


## License
The license is available in the License.txt file in this GitHub repository.

## Community Support
[MATLAB&reg; Central](https://www.mathworks.com/matlabcentral)

Copyright 2024 The MathWorks, Inc.
