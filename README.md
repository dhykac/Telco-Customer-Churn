# Exploratory Data Analysis Telco Customer Churn

In this directory i'm doing exploratory data analysis to Telco_Customer_Churn.csv.

## Preparations

```python
import pandas as pd
import numpy as np
import re

import matplotlib.pyplot as plt
import seaborn as sns
sns.set()

df = pd.read_csv('https://raw.githubusercontent.com/dhykac/Telco-Customer-Churn/main/Telco%20Customer%20Churn.csv',encoding ='latin')
```

## Objectives

Target analysis from this topic is ['Churn'] which is whether the customers from telco company is Churned or not.
The main question of the topic is :
1. What are the reasons (root cause) that makes customers Churned?
2. What is the best option to prevent customers getting Churned?

## Results Preview

![family](https://user-images.githubusercontent.com/92696555/147418978-b3f88401-d624-4383-9daa-87efbdf91647.png)
![online services](https://user-images.githubusercontent.com/92696555/147418999-641cfd69-e23e-4612-a870-5bcc5ceb519a.png)
![streaming services](https://user-images.githubusercontent.com/92696555/147419009-bbe744a1-19ee-4261-aaf4-a79f122db23b.png)

From the analysis, we found that :

* The Telco company had good family contents because the family customers are slightly loyal to the company. But they need to engage the single customers, maybe company can give one-day vacation for loyal customer so they could enjoy quality time for theirself.
* The Telco company not yet seems securable, it cause the people didn't opted for OnlineService and more likely to Churn. The Telco company must added new feature to their OnlineService like online backup storage with encrypted message maybe help engage customer and decrese Churn rate.
* Lastly, the Telco company has little poor of streaming service. So the people with StreamingService more higher chance to Churn. To prevent that, the Telco company must improve their streaming service. How about premium movies for loyal customer with earlier release date than other company?
