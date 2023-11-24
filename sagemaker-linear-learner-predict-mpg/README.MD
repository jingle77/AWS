```python
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split

data = pd.read_csv("FuelEconomy.csv")
data.head()

X = data['Horse Power']
y = data['Fuel Economy (MPG)']

X = np.array(X).astype('float32')
y = np.array(y).astype('float32')

X_train, X_test, y_train, y_test = train_test_split(X,y, test_size=0.30)
```
