# HomePriceRegresion_Modul1
Nasywa Befiputri_2203015044

This Repository is for My Collage SubMission on "introduction to artificial intelligence" Class (Desemebr 2024)

libary
```bash
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error 
import matplotlib.pyplot as plt
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
