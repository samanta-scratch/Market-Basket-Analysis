
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

## Network Graph of relationships between the products
![image](https://user-images.githubusercontent.com/113231185/197387634-23d411e1-90c5-4a04-8fba-cfae82931f59.png)

## Data-driven marketing strategy and decision making

- Item Placements:

Keeping 1.5V IND AAA ALK BULK and 1.5V IND AA ALK BULK in a closer place, maybe in a same shelf or any other closer place

- Products Bundling :

Keeping 1.5V IND AAA ALK BULK and 1.5V IND AA ALK BULK as a single bundle of product with a lower price compare to each price combined -attracting more sales and generates more income

- Customer Recommendation and Discounts:

Keeping 1.5V IND AAA ALK BULK in the cashier, so that every time a customer bought 1.5V IND AA ALK BULK, seller could offer and recommend them to buy 1.5V IND AAA ALK BULK with a lower price

## Conclusions
- Market Basket analysis is done using Apriori Algorithm and Association Rules
- Recommendation is provided for Upselling and Cross Selling through giving ideas of Item Placements, Product Bundling and Applying Discounts
- Rules are visualized through 3D Scatter Plot and Network Graph

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
