# Python Utilities

## Convert Datetime to Unix Timestamp

```py
from datetime import datetime

desired_date = datetime(2020, 1, 1).timestamp()
print(desired_date)
```

```
>>> 1577808000.0
```

## Convert Timestamp to Datetime

```py
from datetime import datetime

timestamp = 1628330971.583739
dt = datetime.fromtimestamp(timestamp)
print(dt)
```

```
>>> datetime.datetime(2021, 8, 7, 18, 9, 38, 365837)
```