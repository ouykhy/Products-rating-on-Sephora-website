<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Products rating on Sephora website products
*[DAFT 2021NOV, Ironhack Paris, 2022 February 11]*

## Content
- [Project Description](#project-description)
- [Methodology](#Methodology)
- [Models](#Models)
- [Links](#links)

## Project Description
The goal is to predict the Sephora website products rating based on its characteristics such as the brand, category, price but also the number of customers appreciation like number of reviews or love. The aim is to issue recommendations on which information is required or will improve the ratings


## Methodology
- Exploratory data analysis 
- Data cleaning and preprocessing
- Models investigation and implementation
- Conclusions

## Models
Supervised ML
|                           | n/estimator  | accuracy score |
|---------------------------|--------------|----------------|
| Logistic regression       |              | 38 %           | 
| KN neighbors Classifier   | 5            | 73 %           | 
| Random Forest Classifier  | 200          | 82 %           | 
| Extra Trees Classifier    | 200,500,1000 | 81 %           |

Unsupervised ML
|                           | n_clusters | Silhouette Coefficient | 
|---------------------------|------------|------------------------|
| k_means                   | 3          | 0.91                   | 
| Agglomerative_clustering  | 3          | 0.88                   | 
| DBSCAN                    | 11         | -0.45                  | 


## Links

[Slides](https://github.com/)  
[Data cleaning](https://)  
[Data cleaning](https://) 



