# Implementation and comparison of FIR digital filters on DSP and FPGA

This paper describes the design and implementation of a finite impulse response (FIR) digital filter on two different development boards, one with a DSP based board with DSK6713 and the other with an FPGA.
In the case of the FPGA, two architectures, both parallel and serial, are analyzed. The performance of the three implementations is analyzed in terms of efficiency, resources and speed. The results show that 
the initial implementation in DSP achieves an adequate performance of the filter, but the implementation of the processing in the FPGA is a significant improvement in terms of speed, capacity and, in the case 
of the serial architecture, an optimization in the consumption of resources
