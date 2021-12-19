# DE0Nano-BSP-Simulink

MathWorks provides support package for several FPGA boards but not for the [DE0-Nano from Terasic](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&CategoryNo=139&No=593).
This project is a custom Board Support Package for the DE0-Nano.

Currently this project only contains the board definition file for HDL Coder FPGATurnkey workflow.
Library of blocks for common functions and examples may be added in the future, however at the moment priority goes to the [DE10-Nano custom board support package](https://github.com/jgui/DE10Nano-BSP-Simulink).

# Getting started

In Matlab, execute function `fpgaBoardManager`, click on button **Add Board from File...** and select file **<>\BoardDefinition\FPGATurnkey\DE0-Nano.xml**.
DE0-Nano board can know be selected in HDL Coder FPGATurnkey workflow.
