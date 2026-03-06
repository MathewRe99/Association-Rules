# Association Rule using Market Basket Dataset

This repository is designed to introduce students to rule mining techniques, with a particular focus on market basket analysis. It provides hands-on experience in applying data mining methods to uncover meaningful associations and patterns within transactional datasets.

# Tools & Libraries
- mlxtend:
Used for implementing the Apriori algorithm and generating frequent itemsets efficiently.
It provides ready-to-use functions for association rule mining, making the analysis more streamlined.
- Apriori Algorithm:
Applied to identify frequent itemsets in transactional data.
The algorithm works by iteratively expanding itemsets and pruning those that do not meet the minimum support threshold.
Key Concepts
- Support:
Measures how frequently an itemset appears in the dataset.
- Confidence:
Indicates the likelihood of item B being purchased when item A is purchased.
- Lift:
Used to evaluate the strength of association between items.
A lift value greater than 1 suggests a positive correlation between items.

Application
- Market Basket Analysis:
By applying Apriori via mlxtend, frequent itemsets were extracted from transactional data.
- Association Rules:
Lift was used to determine meaningful associations between buyers and the items they purchase, helping identify product bundling opportunities and customer buying patterns.

## Authors

- [@MathewRe99](https://www.github.com/MathewRe99)
