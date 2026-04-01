
## Purpose of the Lab

The purpose of this lab was to explore association rule mining techniques 
using Apriori and FP-Growth on the Online Retail dataset. The lab focused 
on identifying frequent itemsets, generating association rules, and 
analyzing purchasing patterns using support, confidence, and lift metrics.

## Key Insights

Both Apriori and FP-Growth identified similar frequent itemsets, including 
popular products such as WHITE HANGING HEART T-LIGHT HOLDER and JUMBO BAG 
RED RETROSPOT. These items appeared frequently across transactions, 
indicating strong customer demand.

FP-Growth was more efficient than Apriori, as it avoids candidate generation 
and uses a tree-based structure. This makes it more suitable for large 
transactional datasets.

The association rules showed strong relationships between related products, 
especially decorative and gift items. High confidence and lift values 
indicated meaningful co-purchasing behavior that could be useful for 
recommendation systems and marketing strategies.

## Challenges and Decisions

One challenge in this lab was converting the dataset into the correct 
basket format. Initially, the data contained quantity values instead of 
binary values, which caused errors in the Apriori algorithm. This was 
resolved by converting the dataset into boolean format.

Another challenge involved installing and configuring required libraries 
such as mlxtend and matplotlib. These issues were resolved by reinstalling 
the packages and ensuring compatibility with the Python environment.

## Files Included

- Lab 6 Jupyter Notebook (.ipynb)  
- README.md
- Online Retail.xlsx 
