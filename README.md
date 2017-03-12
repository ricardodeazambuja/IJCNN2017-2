# IJCNN2017-2

# Experiments used for the paper accepted for [IJCNN2017](http://www.ijcnn.org/)
# Neurorobotic Simulations on the Degradation of Multiple Column Liquid State Machines

## Abstract:
Two different configurations of Liquid State Machine (LSM), a special type of Reservoir Computing with internal nodes modelled as spiking neurons, implementing multiple columns (Modular and Monolithic approaches) are tested against the decimation of neurons, connections and entire columns in order to verify which one can better withstand the damage. Based on the neurorobotics outlook, this work is part of a bigger project that aims to apply artificial neural networks to the control of humanoid robots. Therefore, as a benchmark, we made use of a robotic task where an LSM is trained to generate the joint angles needed to command a simulated version of the collaborative robot BAXTER to draw a square on top of a table. The final drawn shape is analysed through Dynamical Time Warping to generate a cost value based on how close the produced drawing is to the original shape. Our results show both approaches, Modular and Monolithic, had a similar behaviour, however the Modular was better at withstanding the decimation of neurons when it was concentrated in a single column.

This article makes use of the same data generated with the code from [Graceful Degradation under Noise on Brain Inspired Robot Controllers](https://github.com/ricardodeazambuja/ICONIP2016), therefore the readout weights are the [same](https://github.com/ricardodeazambuja/IJCNN2017-2/tree/master/simulation_data_00003/experiment_0001).

Testing was done through a series of notebooks  
1) Modular system
- [Decimation of internal connections](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DATA-TESTER-Modular-Decimated_Internal_Connections.ipynb)
- [Decimation of neurons (all columns)](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DATA-TESTER-Modular-Decimated_Neurons.ipynb)
- [Decimation of neurons (single column)](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DATA-TESTER-Modular-Decimated_Neurons_ind_column.ipynb)
- [Decimation of columns](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DATA-TESTER-Modular-Decimated_Columns.ipynb)

2) Monolithic system
- [Decimation of internal connections](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DATA-TESTER-Monolithic-Decimated_Internal_Connections.ipynb)
- [Decimation of neurons (all columns)](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DATA-TESTER-Monolithic-Decimated_Neurons.ipynb)
- [Decimation of neurons (single column)](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DATA-TESTER-Monolithic-Decimated_Neurons_ind_column.ipynb)
- [Decimation of columns](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DATA-TESTER-Monolithic-Decimated_Columns.ipynb)

3) [Generation of the Cartesian points](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DATA-TESTER-FK.ipynb)

4) [DTW cost](https://github.com/ricardodeazambuja/IJCNN2017-2/blob/master/DWT-TESTER.ipynb)

OBS:  
- [Dynamic Time Warping example](https://github.com/ricardodeazambuja/IJCNN2017/blob/master/DTW_Visualisation_Example.ipynb)
- [Graceful Degradation under Noise on Brain Inspired Robot Controllers](https://github.com/ricardodeazambuja/ICONIP2016)
- [Diverse, Noisy and Parallel: a New Spiking Neural Network Approach for Humanoid Robot Control](https://github.com/ricardodeazambuja/IJCNN2016)
- [BEE SNN simulator](https://github.com/ricardodeazambuja/BEE)

Preprint version:  
- [IJCNN2017-2_draft.pdf](https://github.com/ricardodeazambuja/IJCNN2017-2/raw/master/IJCNN2017-2_draft.pdf)



