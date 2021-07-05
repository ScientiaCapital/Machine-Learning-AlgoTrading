# Venture Funding Prediction Model

Alphabet Soup is a fictional venture capital firm that receives multiple funding applications from startups every day. With the utilization of data containing information from past applicants, this module attempts to create a neural network model which will predict which startups will be successful.

![Venture_Funding_Prediction_Model](https://github.com/ScientiaCapital/Venture-Funding-Deep-Learning-Model/blob/main/Resources/vcimage1.jpeg)

---

## Technologies

The entirety of this notebook was generated via Google Colab. Therefore, you are not required to import any modules onto your personal machine. Below is a list containing all of the Python 3.7 + modules that are utilized in this notebook.

[pandas](https://pandas.pydata.org/pandas-docs/stable/) - Data analysis module

[pathlib](https://docs.python.org/3/library/pathlib.html) - Object-oriented filesystem path module

[sklearn](https://sklearn.org/) - Machine learning module

[tensorflow](https://pypi.org/project/tensorflow/) - High-performance numerical computation library


---

## Installation Guide

With your _Python 3.7+_ environment, run the following commands via CLI:

```
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
```

---

## Examples

![Example_One](https://github.com/ScientiaCapital/Venture-Funding-Deep-Learning-Model/blob/main/Resources/Screen%20Shot%202021-06-24%20at%208.08.01%20AM.png)

![Example_Two](https://github.com/ScientiaCapital/Venture-Funding-Deep-Learning-Model/blob/main/Resources/Screen%20Shot%202021-06-24%20at%208.08.41%20AM.png)

---

## Usage

1. Clone repository onto your personal machine.

2. Open Google Colab.

3. Open venture_funding_with_deep_learning.ipynb within Google Colab.

4. During the section in which the .csv file applicants_data.csv is imported, ensure that this file is present on your personal machine from the repository cloning in Step 1.

5. With the notebook open in Google Colab step through each of the code blocks to review analysis.
---

## Contributors

New development created by Scientia Capital. Code from 'Initial commit.' commit originates from UC Berkeley Extension and I do not claim original ownership nor scholarship.

---

## License

Software tool available for public use. 
