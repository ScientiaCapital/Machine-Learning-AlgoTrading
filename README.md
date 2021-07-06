# Machine Learning AlgoTrading

This notebook consists of analyzing the cumulative returns of two different machine learning algorithms for AlgoTrading.

![Machine_Learning_AlgoTrading](https://github.com/ScientiaCapital/Machine-Learning-AlgoTrading/blob/main/Images/AlgoBot.jpeg)

---

## Technologies

Before attempting to execute any Python code in machine_learning_trading_bot.ipynb, it is imperative that your development environment holds the following modules:

[pandas](https://pandas.pydata.org/pandas-docs/stable/) - Data analysis module

[numpy](https://numpy.org/install/) - Numerical computing module

[pathlib](https://docs.python.org/3/library/pathlib.html) - Object-oriented filesystem path module

[hvplot](https://hvplot.holoviz.org/) - Interactive plotting module

[matplotlib](https://matplotlib.org/) - Plotting module

[sklearn](https://sklearn.org/) - Machine learning module

---

## Installation Guide

With your _Python 3.7+_ environment, run the following commands via CLI:

```
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report

```

---

## Examples

![Example_One](https://github.com/ScientiaCapital/Machine-Learning-AlgoTrading/blob/main/Images/Screen%20Shot%202021-07-05%20at%208.28.24%20PM.png)

![Example_Two](https://github.com/ScientiaCapital/Machine-Learning-AlgoTrading/blob/main/Images/Screen%20Shot%202021-07-05%20at%208.27.58%20PM.png)

![Example_Three](https://github.com/ScientiaCapital/Machine-Learning-AlgoTrading/blob/main/Images/Screen%20Shot%202021-07-05%20at%208.26.28%20PM.png)

---

## Conclusion

Within this notebook, two machine learning algorithms were carried out for the purpose of evaluating their effectiveness for algorithmic trading. The long and short trading windows retained their size across both algorithms and the training / testing data remained somewhat identical. The plots below showcase the cumulative returns of both models across the same time period. From this, we can conclude that the trading strategy proves to be much more effective in generating cumulative returns for the OHLVC dataset as a baseline model.

In the below plots, the SVM and LR Strategy outperforms the Tuned model from mid-2018 towards the end of 2020 in terms of cumulative returns.

---

## Strategy Returns

![Example_Three](https://github.com/ScientiaCapital/Machine-Learning-AlgoTrading/blob/main/Images/Screen%20Shot%202021-07-05%20at%208.27.35%20PM.png)


## Actual

![Example_Four](https://github.com/ScientiaCapital/Machine-Learning-AlgoTrading/blob/main/Images/Screen%20Shot%202021-07-05%20at%208.25.15%20PM.png)

---

## Usage

1. Clone repository onto your personal machine.

2. Open Jupyter Lab or Jupyter Notebook via Anaconda Navigator and navigate to the directory in which the file machine_learning_trading_bot.ipynb is present. All relevant code for this repository will be executed via Jupyter Notebook and no output will be printed to the command line. Ensure that all relevant dependencies and Python modules are installed (see Technologies and Installation Guide for more details) before attempting to execute code within Jupyter Notebook; otherwise, you will receive multiple interpreter errors!

3. With the notebook open, start at the very first cell reading "Machine Learning Trading Bot" (a cell will be active when a rectangular border is surrounding the area in question). Run each cell in sequential order. It is vital that all cells are ran in sequential order or your notebook will generate compiler errors!

---

## Contributors

New development created by Scientia Capital. Code from 'Initial commit.' commit originates from UC Berkeley Extension and I do not claim original ownership nor scholarship.

---

## License

Software tool available for public use. 
