# Spotify_DataAnalysis

***
# Preprocessing of Data Set
```python
#import necessary libraries needed
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import calendar
```

***
### Overview of dataset
1. How many rows and columns does the data set contain?
2. What are the data types of each column? Are there any missing values?
```python
df_spotify = pd.read_csv('spotify-2023 (2).csv', encoding='ISO-8859-1')
df_spotify
```

```python
#Display the number of rows and columns of dataset
df_spotify.info()
```

***

