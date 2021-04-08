# Data Engineering: Multi_Channel Contacts
* Merged user account by using the same contact information. 
* Used data set of Shopee Code League 2021 Data Science in Kaggle (https://www.kaggle.com/c/scl-2021-da/overview)
* The optimal algorithm: Union Find Algorithm  

## Code and Resources Used
**Python Version:** 3.7  
**Algorithm Reference:** https://github.com/deehzee/unionfind   

## Step
* Cluster by Email, Phone, OrderId: 
  - Sort by column
  - if NaN skip, if intersect: union
* Calculate the total contact
