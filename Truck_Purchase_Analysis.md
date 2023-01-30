---
layout: inner
title: Ford Maverick Analysis
permalink: /Truck_Purchase_Analysis/
---
# Ford Maverick Truck Purchase Analysis
### Summary
[Link to another page](/index.html).
### Code

# Start of Analysis

## Price of Car vs Number Sold


```python
import plotly.express as px
df = px.data.iris()
fig = px.scatter(df, x="sepal_width", y="sepal_length", color="species", symbol="species")
fig.show()
```
<iframe src="/Project_Notebooks/plotly_1.html" height = "400px" width = "100%"></iframe>

### Referances

<iframe src="/Resume.pdf" width="100%" height="500px"></iframe>