
## Import packages

```bash
from mlxtend.frequent_patterns import apriori, association_rules
import networkx as nx
```

## Top 15 products by unique purchases

![image](https://user-images.githubusercontent.com/113231185/197387574-fc3a8ee7-e10e-4e9c-980f-d52d10507842.png)


##  Data Processing

  
  <h4>Encoding:</h4> Converting to
  

- 1 for unique quantity >=1
- 0 for unique quantity <=0

## Association Rule Mining


![Fundamentals-of-association-rule-mining-https-doiorg-101371-journalpone0258348g002](https://user-images.githubusercontent.com/113231185/197386047-8b43b1fe-d08b-421f-8de6-30f10be01ac7.png)


## Most Strengthened Rules


```python
rules[(rules['lift'] >= 6) &
       (rules['confidence'] >= 0.5)]
```
