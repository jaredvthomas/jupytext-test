---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.2'
      jupytext_version: 1.9.1
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---

# Testing Jupytext workflow
A simple notebook to see how feasible collaborating using jupytext + git is.
Some more text....

```python
# some imports
import pandas as pd
import numpy as np
```

```python
df = pd.Series(range(10))
df = pd.DataFrame(df)
df['random'] = np.random.randint(0,10,(10,))
```

```python
df = pd.read_csv('output.csv')
```

# Summary
Damn that dataframe is wild yo
