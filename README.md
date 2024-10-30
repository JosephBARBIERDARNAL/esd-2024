# esd-2024

Google collab: https://colab.research.google.com/drive/1oFMkUPCesMIVNmcwa8iRfWrZzWQBoF_l?usp=sharing

<br>

```python
import matplotlib.pyplot as plt
import pandas as pd

data = pd.read_csv("https://github.com/JosephBARBIERDARNAL/misc-dataviz/blob/main/sellbetter.csv?raw=true")
data['Date'] = pd.to_datetime(data['Date'])
data.head(n=10)
```
