# Pandas

## Importing Libraries
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import glob
import re
import math
```

## Printing a Series from Numpy Array
```
v = np.array([1, 2, 3, 4, 5])
s1 = pd.Series(v)
s1
```
<img width="102" height="228" alt="image" src="https://github.com/user-attachments/assets/c193c0cc-bb56-44a8-9550-6869c16b13bf" />


## Printing a Series from list
```
s0 = pd.Series([1,2,3],index = ['a','b','c'])
s0
```
<img width="111" height="174" alt="image" src="https://github.com/user-attachments/assets/7e388d32-d22d-4511-b704-10a6b64950ef" />

## Index in Series
```
s1.index = ['a' , 'b' , 'c' , 'd' , 'e']
s1
```
<img width="102" height="205" alt="image" src="https://github.com/user-attachments/assets/831a3c6d-56d6-411e-b872-43284de7f4b7" />

## Series from Dictionary
```
dict1 = {'a1' :10 , 'a2' :20 , 'a3':30 , 'a4':40}
s3 = pd.Series(dict1)
s3
```
<img width="106" height="174" alt="image" src="https://github.com/user-attachments/assets/01750fea-1f78-48ca-bbde-88abb8e258ac" />

## Printing 99 in indexes
```
pd.Series(99, index=[0, 1, 2, 3, 4, 5])
```
<img width="91" height="231" alt="image" src="https://github.com/user-attachments/assets/60b32498-a179-42c5-8422-d7fffc87fc3e" />

## Slicing

### Returning first elements three elements of series
```
s[0:3]
```
<img width="113" height="140" alt="image" src="https://github.com/user-attachments/assets/f055e302-1833-486b-9bc5-1f27c3fb5f9c" />

### 
