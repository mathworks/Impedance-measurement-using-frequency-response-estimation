# Analyze Battery Impedance Using Exact Linearization

[![View <File Exchange Title> on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/####-file-exchange-title)  

This example shows how to measure the impedance of a battery designed using Simscape™ Battery™ software. You can use impedance analysis to measure the performance and characteristics of a battery.
For a battery modeled using the [Battery Equivalent Circuit block[(https://www.mathworks.com/help/simscape-battery/ref/batteryequivalentcircuit.html), you can analyze the impedance using the linearization
tools from Simulink® Control Design™ software. In this example, you linearize the model at 100% state of charge (SOC) and compare the linearization results with the transfer function that you manually derive
from the equivalent circuit model.This example also shows how to use batch linearization to linearize the model at different SOC levels.


## Setup
Run the livescript 'AnalyzeBatteryImpedanceUsingExactLinearizationExample.mlx'. Ensure you have the necessary MATLAB toolboxes installed (mentioned below).


### MathWorks&reg; Products (https://www.mathworks.com)

Requires MATLAB release R2024a or newer
- [Simulink&reg;](https://www.mathworks.com/products/simulink.html)
- [Simscape&trade;](https://www.mathworks.com/products/simscape.html)
- [Simscape&trade; Battery&trade;](https://www.mathworks.com/products/simscape-battery.html)
- [Control System Toolbox&trade;](https://www.mathworks.com/products/control.html)
- [Simulink&reg; Control Design&trade;](https://www.mathworks.com/products/simcontrol.html)


## License
The license is available in the License.txt file in this GitHub repository.

## Community Support
[MATLAB Central](https://www.mathworks.com/matlabcentral)

Copyright 2024 The MathWorks&reg;, Inc.


