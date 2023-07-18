# Research on hypothesis testing

## Datasets
The two datasets that we have chosen are gathered from [Kaggle](https://www.kaggle.com/). The two datasets that we have compared are phone prices in India with price being in INR and prices of smartphones in US with the price being in USD. The links of the two datsets are: [dataset1](https://www.kaggle.com/datasets/rkiattisak/mobile-phone-price), [dataset2](https://www.kaggle.com/datasets/pratikgarai/mobile-phone-specifications-and-prices).

## Prerequisites
For the following program to work there are a couple of programs to install.
1. [Python 3](https://www.python.org/downloads/)
2. Pip and pandas module
```
pip install pandas
```
3. [Jupyter notebook](https://jupyter.org/)
4. Any code edior, [VS Code](https://code.visualstudio.com/) recommended

## About the project
The projects dives into hypothesis testing of the prices of phones in two different markets India and US. There are a total of two hypothesis \
h0 = The two markets have similar prices \
h1 = The two markets have completely different prices 

Since we are only comparing the prices of two markets and not comparing whether one markets is cheaper and the other way. We are using the two tailed test to complete it.

## Formulae used
z = $x1-x2 \over \sqrt({σ1^2 \over n1} + {σ2^2 \over n2})$ \
Values of two tailed test

| | 1% | 5% | 10% |
| --- | --- | --- | --- |
| Two tailed test | abs(zα) < 2.58| abs(zα) < 1.966 | abs(zα) < 0.645 |
| Right tailed test | zα < 2.33 | zα < 1.645 | zα < 1.28 |
| Left tailed test | zα > -2.33 | zα > -1.645 | zα > -1.28 |