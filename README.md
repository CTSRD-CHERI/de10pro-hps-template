# Template project for Terasic DE10-Pro SX FPGA board

This is an open-source starter project for the DE10-Pro SX FPGA board,
containing an Intel Stratix 10 FPGA, configured for the SX 2800 version.
The SX version contains a quad-core ARM Cortex A53 CPU which is included in
this design.

The default configuration is for HPS boot-first mode, where the ARM cores
are configured to boot from SD card and then program the FPGA (either in
u-boot or via Linux's FPGA manager).  However the project is also usable in
other modes, including downloading via JTAG.

The master branch contains files under an open source licences.  Other
branches may contain files from vendors under more restrictive licences.

At present this has been tested with Quartus Pro version 19.1.

