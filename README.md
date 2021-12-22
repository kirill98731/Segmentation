Segmentation
-------------------------------
Customer segmentation is the process of presenting as separate groups all existing and / or potential customers within one specific market.

## Links to data
Data Set - [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers)

## Data preprocessing

Preprocessing steps:
- Logarithmic normalization
- Linear dimensionality reduction


### Clustering
metric - [f1_scpre](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html)
 - Kmeans ~ 0.9142

### Classification
 - LogisticRegression results ~ 0.9204.  
 - Random Forest results ~ 0.9069.  

 
 ### Conclusion:
Based on the results of segmentation, it can be concluded that the clustering and classification algorithms coped with the task quite well. The results of the algorithms correctly determined the customer segment in 90%. Such an approach can significantly improve the understanding of consumers and makes it possible to adapt the strategy to the specific needs of segments, which will satisfy their requests and have a positive impact on customer potential. The disadvantage of the methods is the need for marked-up data for the possibility of using classification algorithms and interpretation of the clustering model.
 