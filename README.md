# 8x8_SystolicArray_Verilog

This repository contains the verilog code for an 8x8 systolic array.

 Working of the code,
 a).  input_north 1,2... 7 - these wires input the values of the corresponding columns in a pipelined manner and change for every  
      clock cycle 
 b)    input_west 1,2....7 - these wires input the values of the corresponding rows from the west .
 c)    upon calling the block module, the  two inputs are multiplied and are added to the accumulated result. 
 d)    The block code is called 64 times (one for each of the results of the 8x8 matrix ) over 27 clock cycles to complete the entire 
       pipelined operation.
