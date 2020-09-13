# bank-marketing 
<img src="images/Term-Deposit.jpg" >

# Introduction
Nowadays, marketing is so essential for every business to promote their brand image and attract more customers. The cost of marketing is also intimidating, meaning that it is essential for the business to optimize marketing strategies and improve effectiveness. Understanding customers’ need also leads to more effective marketing plans, smarter product designs and greater customer satisfaction.

# Problem Statement and Goal
How can the bank have a greater effectiveness for future marketing campaigns? In order to answer this, we have to analyze the last marketing campaign the bank performed and identify the patterns that will help us find conclusions in order to develop future strategies. 

Our goal is to find the best strategies to improve for the next marketing campaign to better target customers who are more likely to subscribe term deposits. The bank can then put more effort into marketing these customers. This will not only help the bank get more deposits but also save unncessary marketing expenses on those people who will not subscribe.

# Data Collection
This dataset is about the direct phone call marketing campaigns, which aim to promote term deposits among existing customers, by a Portuguese banking institution from May 2008 to November 2010. It is publicly available in the [UCI Machine learning Repository.](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing#)

# Preprocessing
- Generally speaking, the dataset is in good condition with no missing values and duplicates and with mix of categorical and numerical variables.
- According to what the data description shows, outliers in one of the core columns 'balance' have been detected and been removed based on IQR rule.
- For easy understanding, yes/no in the target column has been converted into 1/0 and -1 in the pdays has been converted into 0, which means the client has not been contacted.

# Explanatory Data Analysis
<img src="images/dist1.jpg" >
