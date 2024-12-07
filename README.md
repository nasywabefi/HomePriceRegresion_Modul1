# HomePriceRegresion_Modul1
Nasywa Befiputri_2203015044

This Repository is for My Collage SubMission on "introduction to artificial intelligence" Class (Desemebr 2024)

libary
```bash
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error
from sklearn.preprocessing import MinMaxScaler
from sklearn.preprocessing import StandardScaler
from sklearn.preprocessing import PolynomialFeatures
from sklearn.pipeline import make_pipeline 
```

add to code
```bash
url = "https://raw.githubusercontent.com/nasywabefi/HomePriceRegresion_Modul1/main/HousingData.csv"
df_boston = pd.read_csv(url, encoding='ISO-8859-1')  # Gunakan encoding yang sesuai
# Tampilkan 5 baris pertama
df_boston.head()
```

cek info data
```bash
df_boston.info()
```
