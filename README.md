# CGCT-RM-MEDA
Code for "A Centroid Guided Cluster Transformation for Dynamic Multi-Objective Optimization Algorithm"

# Abstract
In recent years, prediction-based algorithms have made significant progress in solving dynamic multi-objective optimization problems (DMOPs). However, most existing algorithms only consider information from several consecutive environments and ignore previous search experiences. This article uses the search experience of the Regularity Model-Based Multiobjective Estimation of Distribution Algorithm (RM-MEDA) to propose a dynamic multiobjective optimization algorithm based on the centroid-guided cluster transformation (CGCT-RM-MEDA). When the environment changes, the information from the statically optimized model in the previous environment is used to estimate a new distribution model through a cluster transformation. At the same time, the location of the population distribution is predicted using a Long Short-Term Memory (LSTM) network, which is used to estimate the cluster centers of the model distribution. The empirical study evaluated the performance of CGCT-RM-MEDA using 14 benchmark functions and one performance metric.  The experimental results show that CGCT-RM-MEDA outperforms seven peer algorithms in performance.

# Reference
> @INPROCEEDINGS{CGCT,
> author={Zeng, Yi and Xia, Xuewen and Lin, Fenglin and Zhang, Yuehui and Liu, Meitong},
> booktitle={2025 IEEE Congress on Evolutionary Computation (CEC)},
> title={A Centroid Guided Cluster Transformation for Dynamic Multi-Objective Optimization Algorithm},
> year={2025},
> pages={1-8}
> }

# Usage
- MATLAB 2024b
- run main.m
