# SDSC4016 Fundamentals of Machine Learning II

SDSC4016 Homework 1:

- [On Kaggle](https://www.kaggle.com/competitions/sdsc4016-fundls-of-ml-2-hw1/overview)

## Description

Solve a regression problem (COVID-19 prediction) with deep Multilayer Perceptron (MLP).

## Getting Started

### Dependencies

- Python
  - Python 3.10+
  - Jupyter
  - pytorch

### Install mini-conda and mamba

```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash ./Miniconda3-latest-Linux-x86_64.sh
conda install mamba -n base -c conda-forge
```

### Set up conda environment

```bash
mamba create -n 4016hw1
mamba activate 4016hw1
```

### Installing dependencies

```bash
# conda or mamba
mamba install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
mamba install -c conda-forge Jupyter ipykernel
mamba install -c conda-forge pandas numpy seaborn matplotlib scikit-learn
```

### Code

[Weak Baseline](src/Baseline.ipynb)

[Strong Baseline](src/Modified.Private.ipynb)

### Dataset

[Training set](data/HW1.train.csv)

[Testing set](data/HW1.test.csv)

### Tested Result on Kaggle

[Results on Kaggle](md/kaggle.md)

### Final Score (Strong Baseline)

- Public: Personal Best - 0.85156 vs Given Answer - 0.85584
- Private: Personal Best - 0.89874 vs Given Answer - 0.91165
