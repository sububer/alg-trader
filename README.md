# alg-trader
FinTech Challenge 14 -- ML Alg Trading Bot

See full implementation and notebook details in [machine_learning_trading_bot.ipynb](app/machine_learning_trading_bot.ipynb)  

---

## Overview Of Analysis

Improving algorithmic trading systems by enhancing existing trading signals with ML algorithms.  

At a high-level, the following will be performed:  
- implement an algorithmic trading strategy that uses machine learning to automate trade decisions
- adjust input parameters to optimize the trading algorithm
- train a new machine learning model and compare its performance to that of a baseline model
- create an evaluation report that compares performance of each enhancement/model  

See full implementation and notebook details in [machine_learning_trading_bot.ipynb](app/machine_learning_trading_bot.ipynb)  

---  

## DataSet Details  

Data sets used to anlyze this space:
- [emerging_markets_ohlcv.csv](data/emerging_markets_ohlcv.csv) OHLCV data for an [MSCI-based emerging markets ETF](https://www.ishares.com/us/products/268704/ishares-currency-hedged-msci-emerging-markets) from iShares
    - contains data: `date | open | high | low | close | volume` from Jan 21, 2015 -> Jan 27, 2015 in 15-min intervals  

---  

## Model Tuning Results

### Baseline

TBD  

**Baseline Model Performance**  
![Baseline Performance](media/01_baseline_cum_returns.png)  

### Adjusted Training Dataset Size

TBD  

### Adjusted SMA Input Features

TBD  

### Parameter Tuning: Conclusions

TBD  


## New Machine Learning Classifier

TBD  

### New Classifier Results

Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?  


## Summary Evaluation

TBD  -   For this report, express your final conclusions and analysis. Support your findings by using the PNG images that you created.  


See full implementation and notebook details in [machine_learning_trading_bot.ipynb](app/machine_learning_trading_bot.ipynb)  


---

## Technologies

This challenge uses [python](https://www.python.org/) 3.7 and the following [built-in](https://docs.python.org/3/py-modindex.html) modules:
- [os](https://docs.python.org/3/library/os.html#module-os)
- [pathlib](https://docs.python.org/3/library/pathlib.html)
- [datetime](https://docs.python.org/3/library/datetime.html)

Additionally, it requires:
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/)
- [scikit-learn](https://scikit-learn.org/stable/index.html)
- [hvplot](https://hvplot.holoviz.org/)  

See [installation](#installation) below for specifics.

---

## Installation

You will need Python 3.7, that supports for this application to run. An easy way to install python 3.7 is to download and install [Anaconda](https://www.anaconda.com/products/individual). After installing anaconda, open a terminal/command-prompt, and setup a python 3.7 environment, and then activate it like so:

```
# create an anaconda python 3.7 environment
# name can be any friendly name to refer to your environment, eg 'dev'
conda create --name dev python=3.7 anaconda

# activating the environment
conda activate dev

# use pip to install the above modules, eg:
pip install python-dotenv
...etc...
```


---

## Usage

The analysis is presented within a [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) notebook. To launch JupyterLab, from the root of this repo dirctory:

```
# within repo root 
$ jupyter lab
```
You can now open and run the notebook [machine_learning_trading_bot.ipynb](app/machine_learning_trading_bot.ipynb)  

---

## Contributors

[David Lopez](https://github.com/sububer)

---

## License

MIT