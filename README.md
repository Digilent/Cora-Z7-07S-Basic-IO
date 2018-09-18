Cora-Z7-07S-Basic-IO Demo
==============

Description
--------------
This project is a Vivado demo using the Cora Z7-07S's RGB LED's and pushbuttons, written in Verilog. When programmed onto the board, the RGB LEDs will cycle from Blue to Green to Red to Black. As long as one of the two buttons is pushed, the corresponding RGB LED will be turned off.

Requirements
--------------
* **Cora-Z7-07S**:To purchase a Cora-Z7-07S, see the [Digilent Store](https://store.digilentinc.com/cora-z7-zynq-7000-single-core-and-dual-core-options-for-arm-fpga-soc-development//)
* **Vivado 2018.2 Installation**:To set up Vivado, see the [Installing Vivado and Digilent Board Files Tutorial](https://reference.digilentinc.com/vivado/installing-vivado/start).
* **MicroUSB Cable**
 
Demo Setup
--------------
1. Download and extract the most recent release ZIP archive from this repository's [Releases Page](https://github.com/Digilent/Cora-Z7-07S-Basic-IO/releases).
2. Open the project in Vivado 2018.2 by double clicking on the included XPR file found at "\<archive extracted location\>/vivado_proj/Cora-Z7-07S-Basic-IO.xpr".
3. In the Flow Navigator panel on the left side of the Vivado window, click **Open Hardware Manager**.
4. Plug the Cora-Z7-07S into the computer using a MicroUSB cable.
5. In the green bar at the top of the Vivado window, click **Open target**. Select **Auto connect** from the drop down menu.
6. In the green bar at the top of the Vivado window, click **Program device**.
7. In the Program Device Wizard, enter "\<archive extracted location\>vivado_proj/Cora-Z7-07S-Basic-IO.runs/impl_1/top.bit" into the "Bitstream file" field. Then click **Program**.
8. The demo will now be programmed onto the Cora-Z7-07S. See the Description section of this README to learn how to interact with this demo.

Next Steps
--------------
This demo can be used as a basis for other projects, either by adding sources included in the demo's release to those projects, or by modifying the sources in the release project.

Check out the Cora-Z7-07S's [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/cora-z7/start) to find more documentation, demos, and tutorials.

For technical support or questions, please post on the [Digilent Forum](https://forum.digilentinc.com).

Additional Notes
--------------
For more information on how this project is version controlled, refer to the [Digilent Vivado Scripts Repository](https://github.com/digilent/digilent-vivado-scripts)


