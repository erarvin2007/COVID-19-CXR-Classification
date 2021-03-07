# COVID CXR Model | GPU (Compatible with CPU)


## Introduction
This project uses chest x-ray scans to predict if a patient has COVID-19. The COVID CXR Model was inspired by [COVID-Net](https://www.nature.com/articles/s41598-020-76550-z#citeas). A Jupyter Notebook, *COVID.ipynb*, which can be executed in order to train the model is included in the repository. In order to run the notebook, [tqdm](https://pypi.org/project/tqdm/), [PyTorch](https://pytorch.org/get-started/locally/) and [Python 3](https://www.python.org) must be installed on your machine. The Jupyter Notebook is compatible with both GPUs (recommended) and CPUs. The pretrained network's saved parameters can be found at *COVID.prm*.

Note: The COVID CXR Model is still in developmental stage and should not be used for self-diagnosis.

Support: erarvin2007@gmail.com

### Dataset
This repository uses the COVIDx Binary dataset which are generated using scripts that can be accessed on [this](https://github.com/lindawangg/COVID-Net) repository. 

|  Type | COVID-19 Negative | COVID-19 Positive | Total |
|:-----:|:------:|:---------:|:--------:|
| train |  13794  |    1670   |    15464   |
|  test |   100  |     100   |   200    |
