# Implementation of a digital electromyographic signal processor synthesized on an FPGA development board for biocontrol systems

This paper presents the design and synthesis of a digital electromyo graphic signal processor applying dedicated processing methods and pattern recognition for the classification of upper limb movements 
of the human body. To accelerate the digital processing of EMG signals and reduce the implementation hardware, the system is integrated with a Field Program Gate Array in which the digital processing techniques 
are implemented at hardware level, from signal filtering to pattern recognition and classification, also, the analog to digital converter of a microcontroller is used for the acquisition of the EMG signal.
The modules neces sary for the first steps of digital processing are designed and synthesized in Verilog HDL. After obtaining and characterizing the signal, from registered signal values in MATLAB, the simple
perceptron training algorithm is used to obtain the synaptic weights of the perceptron, which are then implemented in the FPGA design for the perceptron module in hardware. After implementing the complete system
and performing the tests, the signals obtained are analysed with their classification and the percentage of success, with results of 70% and 80% person A and 60% and 80% for persond B for contraction and extension,
respectively; it should be noted that the complete system was only tested on two people.
