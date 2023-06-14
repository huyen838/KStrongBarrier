# KStrongBarrier

This repository includes experimental data, data visualization and experimental results of the proposin algorithm in the manuscript "An efficient approach to the $k$-strong barrier coverage problem under the probabilistic sensing model in wireless multimedia sensor network".

## Data and Visualization

The "Data" folder contains all the generated data for evaluating the performance of the proposed algorithm, referred to as KSB-EA, as well as for comparison with the state-of-the-art approaches, namely KCES and AIPSO.

The data files are named based on specific parameters: the number of stationary sensors (NS), half of the sensing angle (A) in the case of small-scale networks, and the sensor distribution type in the network (UNI for uniform, GAU for normal/gaussian, or EXP for exponential distribution). 

The data files within the "W100-H020" folders correspond to small-scale networks, while the data files within the "W500-H100" folders correspond to large-scale networks.

Each .txt file within the dataset contains detailed information about a specific network configuration. The first line of each file provides the width, height of the Region of Interest (RoI), and the total number of stationary sensors, presented in that respective order. 

The subsequent $NS$ lines in the file correspond to each individual sensor within the network. Each line contains information about the sensor's position, radius, half of the sensing angle, and orientation angle. These details provide a comprehensive description of the sensor's characteristics within the network configuration.

The "Visualization" folder presents some visualization of some example networks.

## Result

The "Raw Results" folder contains raw results returned by each algorithm. The "Plotting and Comparison Results" introduce the charts in the paper and codes to generate it.


