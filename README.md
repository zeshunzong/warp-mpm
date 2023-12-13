# WARP MPM
<p align="center">
  <img src="assets/sand.gif">
</p>

This MPM solver is implemented using Nvidia's WARP: https://nvidia.github.io/warp/

This solver is used in 
```
Neural Stress Fields for Reduced-order Elastoplasticity and Fracture
Zeshun Zong, Xuan Li, Minchen Li, Maurizio M. Chiaramonte, Wojciech Matusik, Eitan Grinspun, Kevin Carlberg, Chenfanfu Jiang, Peter Yichen Chen.
SIGGRAPH Asia. 2023.
```
and 
```
PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics
Tianyi Xie*, Zeshun Zong*, Yuxing Qiu*, Xuan Li* (equal contributions), Yutao Feng, Yin Yang, Chenfanfu Jiang.
Arxiv. 2023.
```

For details about MPM, please refer to the course on the Material Point Method: https://www.math.ucla.edu/~cffjiang/research/mpmcourse/mpmcourse.pdf


## Prerequisites

This codebase is tested using the environment with the following key packages:

- Ubuntu 20.04
- CUDA 11.6
- Python 3.9.13
- Warp 0.10.1

## Installation
```
pip install -r requirements.txt
```

## Examples
Sand: column collapse 
```
python run_sand.py
```
We allow flexible interactions with PyTorch, which makes it a great building block for Machine Learning + Simulation.

## If this helps you, please cite us!
```
@inproceedings{10.1145/3610548.3618207,
author = {Zong, Zeshun and Li, Xuan and Li, Minchen and Chiaramonte, Maurizio M. and Matusik, Wojciech and Grinspun, Eitan and Carlberg, Kevin and Jiang, Chenfanfu and Chen, Peter Yichen},
title = {Neural Stress Fields for Reduced-Order Elastoplasticity and Fracture},
year = {2023},
isbn = {9798400703157},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3610548.3618207},
doi = {10.1145/3610548.3618207},
booktitle = {SIGGRAPH Asia 2023 Conference Papers},
articleno = {78},
numpages = {11},
keywords = {Neural field, reduced-order model, the material point method, model reduction},
series = {SA '23}
}
```
