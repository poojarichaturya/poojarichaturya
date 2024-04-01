import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
from scipy.stats import norm
from sklearn.preprocessing import StandardScaler
from scipy import stats
import warnings
warnings.filterwarnings('ignore')
%matplotlib inline
In [2]:
#bring in the six packs
df_train = pd.read_csv('../input/train.csv')
In [3]:
#check the decoration
df_train.columns
<!---
poojarichaturya/poojarichaturya is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
