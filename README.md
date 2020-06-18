# Age-structured estimation of COVID-19 ICU demand from low quality data

## Description

Code for *Age-structured estimation of COVID-19 ICU demand from low quality data*.

Paper link: [arXiv:2006.06530](https://arxiv.org/abs/2006.06530)

## Prerequisites
- [python](https://www.python.org/) >= 3.6
- [numpy](https://www.numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [scipy](https://www.scipy.org/)
- [scikit-learn](https://scikit-learn.org/stable/)

Typically, [Anaconda](https://www.anaconda.com/distribution/) distribution for Python >= 3.6 is enough. 

## Usage

The main results are calculated in 

- `sampler_state_SP.ipynb`.
- `sampler_city_SP.ipynb`.

The respective plots are constructed in

- `plots_main.ipynb`

Further analysis about other cities and regions can be readly performed as shown in:

- `sampler_grande_SP.ipynb`.

Data epidemic evolution plots:

- `plots_data_ep_evol.ipynb`

Constructions of epidemic scenarios:

- `scenarios.ipynb`


Folders with data, saved results and paper figures, respectively:

- `data`
- `results/dfs`
- `results/figures`


