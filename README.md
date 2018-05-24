This project is a a simple Verilog demo using the Cora Z7-07S's RGB LEDs and buttons. When programmed onto the board, the RGB LEDs will cycle from Blue to Green to Red to Black. As long as one of the two buttons is pushed, the corresponding RGB LED will be turned off.

For the Cora Z7-10 version of this project, see [this repo](https://github.com/Digilent/Cora-Z7-10-Basic-IO).

WARNING!!! This project is only supported in the 2017.4 version of Vivado.

In order to program the project onto an FPGA:

1. 	Download the most recent release ZIP archive (not the source ZIP) from the repo's [releases page](https://github.com/Digilent/Cora-Z7-07S-Basic-IO/releases).

2. 	Extract and open the downloaded ZIP. Double click on "Cora-Z7-07S-Basic-IO.xpr". This will launch an archived version of the project, in which a bitstream has already been generated.

3. 	Open the Vivado Hardware Manager, select "Open Target", and find the target board.

4.  Program top.bit, found in the Cora-Z7-07S-Basic-IO.runs/impl_1/ subdirectory of the extracted archive, onto the target.

For more information on how this project is version controlled, see the [digilent-vivado-scripts repo](https://github.com/artvvb/digilent-vivado-scripts), which contains several Python and TCL scripts for maintaining a Vivado project on Github.
