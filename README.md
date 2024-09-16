# MORL Notebooks

A collection of notebooks for multi-objective reinforcement learning.

This repository is based on [LucasAlegre/morl-baselines (Github)](https://github.com/LucasAlegre/morl-baselines).

> Note: We assume that you are familiar with single-objective RL and basic concepts of multi-objective RL.

## Notebooks

Other notebooks will be added in the future.

| Name | SER/ESR | Paper
| --- | --- | --- |
| [Pareto Q-Learning](pql.ipynb) | SER | [Paper](https://www.jmlr.org/papers/volume15/vanmoffaert14a/vanmoffaert14a.pdf)

## Installation

Create a new conda environment and activate it:

```bash
conda create -n morl-notebooks python=3.10 -y
conda activate morl-notebooks
```

Then, install the required packages:

```bash
pip install torch==2.4.1
pip install mo-gymnasium==1.1.0
pip install ipykernel
pip install tqdm
```

> Note: The package list can be changed in the future.
