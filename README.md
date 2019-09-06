# DROO

*Deep Reinforcement Learning for Online Computation Offloading in Wireless Powered Mobile-Edge Computing Networks*

Python code to reproduce our works on Wireless-powered Mobile-Edge Computing [1], which uses the wireless channel gains as the input and the binary computing mode selection results as the output of a deep neural network (DNN). It includes:

- [memory.py](memory.py): the DNN structure for the WPMEC, inclduing training structure and test structure

- [data](./data): all data are stored in this subdirectory, includes:

  - **data_#.mat**: training and testing data sets, where # = {10, 20, 30} is the user number

- [main.py](main.py): run this file for DROO, including setting system parameters

- [demo_alternate_weights.py](demo_alternate_weights.py): run this file to evaluate the performance of DROO when WDs' weights are alternated

- [demo_on_off.py](demo_on_off.py): run this file to evaluate the performance of DROO when some WDs are randomly turning on/off


## About our works

1. Liang Huang, Suzhi Bi, and Ying-jun Angela Zhang, **Deep Reinforcement Learning for Online Computation Offloading in Wireless Powered Mobile-Edge Computing Networks**, *IEEE Transactions on Mobile Computing*, [early access](https://ieeexplore.ieee.org/document/8771176). Preview available on [arxiv:1808.01977](https://arxiv.org/abs/1808.01977).

## About authors

- Liang HUANG, lianghuang AT zjut.edu.cn

- Suzhi BI, bsz AT szu.edu.cn

- Ying Jun (Angela) Zhang, yjzhang AT ie.cuhk.edu.hk

## Required packages

- Tensorflow

- numpy

- scipy

## How the code works

- For DROO algorithm, run the file, [main.py](main.py)

- For DROO demo with laternating-weight WDs, run the file, [demo_alternate_weights.py](demo_alternate_weights.py)

- For DROO demo with ON-OFF WDs, run the file, [demo_on_off.py](demo_on_off.py)
