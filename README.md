# MaDIoT-2.0 Test Cases and Simulation Files

## What is MaDIoT 2.0?

MaDIoT 2.0 is a novel manipulation of demand attack on power grids, where the adversary can change the loads in system nodes using a high-wattage IoT botnet to cause blackout in the target grid. We release two test cases in this repository to enable the future researchers use them as benchmarks for evaluating the performance of their IoT bontnet-based attacks.


## What You Can Find Here?
There are three main directories in the repository: i) Data, ii) Scripts, and iii) Test Grids. The "Data" directory contains all the basic data required to run the scripts and the grid simulations. The "Scripts" directory include several Matlab scripts for calculating the voltage stability indices, power flows in branches and nodes, and load shedding. Finally, the "Test Grids" directory includes the simulation files of two test grids: i) IEEE 9 node and ii) IEEE 39 node systems. 


## How You Can Use the Test Grids?
All the scripts were written in Matlab becuase it is easy to link it with the grid simulator. In order to run the scripts, you need to install Matlab in your machine. The test grids were modeled in a state-of-the-art simulator called DIgSILENT Power Factory. To run the test grids, you need to install the DIgSILENT Power Factory on your machine and simply import the test grids. Then, you can execute time domain simulations using the RMS analysis in the software. You can define various attack scenarios to be simulated in the test cases and evaluate their performances by monitoring the operating status of the grids in the software. This can be easily automated by linking the DIgSILENT Power Factory with Matlab.

## Bugs, Issues, and Suggestions?
Please feel free to share any bugs, issues, and suggestions with us by sending an email to madiot20@gmail.com. Any feedback is greatly appreciated.
