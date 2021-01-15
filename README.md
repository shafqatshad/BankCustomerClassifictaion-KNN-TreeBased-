# BankCustomerClassifictaion-KNN-TreeBased-
Dataset source:https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

Originally we cleaned a data set with ~1200 rows. We took 519 rows that were ‘yes’, randomized the remaining ones that were ‘no’, and then pulled 600 of those
We then decided that was too small and went to work on the data set with 45,000 rows, but there were a lot of missing values and issues
The 3rd data set was one that was around 4,500 rows, we decided to work with because it was preprocessed and didn’t have the issues we saw on the larger one
We then took out 3 columns, ‘days,’ which was day of the month, ‘poutcome’, which was outcome of the previous marketing campaign , which had categorical values of,
'failure','nonexistent','success'. The third column we took out was ‘contact’, which was contact communication type, made up of categorical values,'cellular','telephone').
We decided to eliminate days and contacts because we didn’t think those were relevant predictors and 
we took out poutcome because most of the values were ‘unknown’ and didn’t fall into any of the categories that were mentioned above. 

