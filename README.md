# MLN601_Assessment_3

Repository for the 3rd Assessment.

# Load the data
The following code can be used to import a wine quality red CSV file containing 1600 samples:

```python
import pandas as pd

data = pd.read_csv('https://raw.githubusercontent.com/Miragencia/MLN601_Assessment_3/main/bike%2Bsharing%2Bdataset/day.csv',
                   sep=';', encoding='utf8')
```

Data source: (https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset)
