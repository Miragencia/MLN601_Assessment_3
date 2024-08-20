# MLN601_Assessment_3
https://github.com/Miragencia/MLN601_Assessment_3/blob/main/README.md
Repository for the 3rd Assessment.

# Load the data
The following code can be used to import a wine quality red CSV file containing 1600 samples:

```python
import pandas as pd

data = pd.read_csv('https://raw.githubusercontent.com/Miragencia/MLN601_Assessment_3/main/wine%2Bquality/winequality-red.csv',
                   sep=';', encoding='utf8')
```

Data source: (https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset)
