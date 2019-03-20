---
title: 'Python Kullanımını Deniyoruz'
description: 'Chapter description goes here.'
free_preview: true
---

## Deneme

```yaml
type: NormalExercise
key: f6683e8306
xp: 100
```

Bu bir python kodlama denemesidir

`@instructions`


`@hint`
np.arrange will create a  number series .

`@pre_exercise_code`
```{python}
import numpy as np 
import pandas as pd 

```

`@sample_code`
```{python}
ser= np.arange()
col=
mean=
```

`@solution`
```{python}
ser=np.arange(100)
col=pd.Series(ser)
mean=col.mean()
```

`@sct`
```{python}
Ex().check_object("ser").has_equal_value()
Ex().check_object("col").has_equal_value()
Ex().check_object("mean").has_equal_value()
```

---

## deneme 2

```yaml
type: NormalExercise
key: 14e053b1d9
xp: 100
```

deneme2

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}
import pandas as pd 
trainloan=pd.read_csv("https://assets.datacamp.com/production/repositories/4802/datasets/110bceb7393170db1d6b7921782d81074df70556/train_loan.csv")

```

`@sample_code`
```{python}
collist=
```

`@solution`
```{python}
collist=trainloan.columns
```

`@sct`
```{python}
Ex().check_object("collist").has_equal_value()
```
