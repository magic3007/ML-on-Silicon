# ML on Silicon

🐱‍👤 A collection of works on neural networks and neural accelerators.

## Table of Contents

[TOC]

## Conference Papers

Papers of significance are marked in **bold**. My comments are marked in *italic*. Papers of other fields may also included, and we use the following tags to categorize different fields.

- ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) Neuromorphic Hardware
- ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) ISA
- <img src="https://placehold.it/15/af62ff/000000?text=+" alt="#af62ff" /> Compiler
- <img src="https://placehold.it/15/f4f442/000000?text=+" alt="#f4f442" /> Distributed Machine Learning

- <img src="https://placehold.it/15/ece5b8/000000?text=+" alt="#ece5b8" /> Homomorphic Computing

### 2020 Preprints

- ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) An Instruction Set Architecture for Machine Learning(CAS, China, Yunji Chen)
  - Citing: TABLA

### 2020 ASPLOS

- <img src="https://placehold.it/15/af62ff/000000?text=+" alt="#af62ff" /> FlexTensor: An Automatic Schedule Exploration and Optimization Framework for Tensor Computation on Heterogeneous System(Peking University, Yun Liang)
    - source code: https://github.com/KnowingNothing/FlexTensor
- <img src="https://placehold.it/15/f4f442/000000?text=+" alt="#f4f442" /> Prague High-Performance Heterogeneity-Aware Asynchronous Decentralized Training(USC)
- <img src="https://placehold.it/15/af62ff/000000?text=+" alt="#af62ff" /> Interstellar: Using Halide’s Scheduling Language to Analyze DNN Accelerators(Standard University, Mingyu Gao)

### 2019 ASPLOS

- ![#f03c15](./README.assets/000000-1586508020274.png) PUMA: A Programmable Ultra-efficient Memristor-based Accelerator for Machine Learning Inference
  
  - Citing: TABLA
- ![#f03c15](./README.assets/000000-1586508058898.png) FPSA: A Full System Stack Solution for Reconfigurable ReRAM-based NN Accelerator Architecture(Yu Ji, Youhui Zhang, Yuan Xie, Tsinghua University, UCSB)

### 2019 HPCA

- <img src="https://placehold.it/15/ece5b8/000000?text=+" alt="#ece5b8" /> FPGA-based High-Performance Parallel Architecture for Homomorphic Computing on Encrypted Data
  - source code: https://github.com/KULeuven-COSIC/HEAT

### 2019 ISCA

- ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) Cambricon-F: Machine Learning Computers with Fractal von Neumann Architecture(CAS, China, Yunji Chen)

### 2018 ASPLOS

- ![#f03c15](./README.assets/000000-1586508058898.png) Bridge the Gap between Neural Networks and Neuromorphic Hardware with a Neural Network Compiler(Yu Ji, Youhui Zhang, Yuan Xie, Tsinghua University, UCSB)
  - *transform a computation graph into hardware execution model that only consists of core-op, including max-pooling, convolution & quantization*
  - See more info mapping & scheduling strategy in <u>TrueNorth</u>.

### 2018 FCCM

- FlexiGAN: An End-to-End Solution for FPGA Acceleration of Generative Adversarial Networks(ACT lab)
  - Citing: TABLA

### 2018 ISCA

- Bit Fusion: Bit-Level Dynamically Composable Architecture for Accelerating Deep Neural Network(ACT lab)


### 2017 MICRO

- Scale-Out Acceleration for Machine Learning, CoSMIC(ACT lab)

  - Citing: TABLA
  
### 2016 MICRO

- ![#c5f015](./README.assets/000000-1586508246163.png) From High-Level Deep Neural Models to FPGAs, DNNWeaver(ACT lab)
  - Citing: TABLA
- ![#f03c15](README.assets/000000-1586511629806.png) NEUTRAMS: Neural network transformation and co-design under neuromorphic hardware constraints(Yu Ji, Youhui Zhang, Yuan Xie, Tsinghua University, UCSB)

### 2016 HPCA

- TABLA: A Unified Template-based Framework for Accelerating Statistical Machine Learning(ACT lab)

  - source code: https://bitbucket.org/act-lab/tabla/

-  ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) PipeLayer: A Pipelined ReRAM-Based Accelerator for Deep Learning

   -  Citing: PRIME, TABLA, ISAAC

## How to Start Up Your Experiments?

To conduct a experiment, datasets, toolchains, hardware configuration, evaluation statistics and etc. should be taken into consideration. This collection is hosted on [*Google Sheet*](https://docs.google.com/spreadsheets/d/1O-a3oIsR5ElIl7xz6YzjLmoaF0d9hzIYFvrWodcBTWs/edit?usp=sharing) for the convenience of editing. Also, some toolkits may help improve the quality of life! 🚀 

### Toolkits

- **hlslib**: A collection of extensions for Vivado HLS and Intel FPGA OpenCL to improve developer quality of life.
    - source code: https://github.com/definelicht/hlslib

## Important Issues

This is a collection of papers on other important topics related to neural networks. Papers of significance are marked in **bold**. My comments are in marked in *italic*.

### Tutorial & Survey

- [CSE 240D: Accelerator Design for Deep Learning (Winter 2019)](https://hadiclass.github.io/cse240d-wi19/schedule.html) (UCSD)
- [CSE 599W: SysML](http://dlsys.cs.washington.edu/) (UW)
- [AI Computing Systems by *Yunji Chen*](http://novel.ict.ac.cn/aics/)

###  Forum

- [Cambricon Forum](http://forum.cambricon.com/list-1-1.html)

### Lab & Prof.

- [Hadi Esmaeilzadeh](http://cseweb.ucsd.edu/~hadi/). ACT Lab, Georgia Institute of Technology, UCSD

