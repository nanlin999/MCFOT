# MCFOT
Code of the paper "MCF-adjusted Ordered Testing Procedures on Multiple Discrete Tests with Prior Information" by Xiaoyu Dai and Nan Lin. 

Part of the code is based on the [code](https://www.stat.uchicago.edu/~rina/accumulationtests.html#code.) for paper "Accumulation tests for FDR control in ordered hypothesis testing" by Ang Li and Rina Foygel Barber.

## src

* AT_randp: AT and AT-MCF.
* MCF_main: MCF-based discrete multiple testing function for ordered multiple testing problem.
* data: simulating multiple testing data from Fisher's Exact Tests.
* mcf.cpp: calculating MCF values usign cpp.
* methods: SS, AS, SS-MCF and AS-MCF.
* multiplot: multiple ggplots wintin one figure.
* performance: evaluation by FDP and statistical power.

## simu

* main: one-time simulation
* main_rep: simulations with repeated samples.

## real

* MCFOT_wgbs: application of MCFOT on wgbs data described in "MCF-adjusted Ordered Testing Procedures on Multiple Discrete Tests with Prior Information" by Xiaoyu Dai and Nan Lin. 
* dose_AT_randp: application of MCFOT on dose data descried in "Accumulation tests for FDR control in ordered hypothesis testing" by Ang Li and Rina Foygel Barber.
