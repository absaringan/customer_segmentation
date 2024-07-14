# Personality Profiling: Customer Segmentation through Clustering Techniques
![title](https://github.com/user-attachments/assets/36b50fe4-4dde-4878-8470-43c721c596e5)

The goal of the project is the split customers into distinct profiles and recommend tailored marketing strategies per segment.
The project employs hierarchical clustering methods on customers' personal features, purchase behaviors and preferences to identify each customer profile.

## Data Source
Customer Personality Analysis dataset from Kaggle.  
Link: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis

## Methodology
![methodology](https://github.com/user-attachments/assets/9580c804-1895-4893-998d-5c100cdbadc5)
| Step | Process                         | Description                                                                                                                                         |
|:-----|:--------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------|
| 1    | Data Cleaning and Preprocessing | Prepare the dataset by handling missing values, mapping ordinal values, one-hot encoding nominal features, and excluding unnecessary features       |
| 2    | Dimensionality Reduction        | Standardize the data and perform dimensionality reduction via PCA                                                                                   |
| 3    | Hierarchical-based Clustering   | Plot the dendrogram to determine threshold and perform clustering via Ward's method to determine the clusters                                       |
| 4    | Results and Discussion          | Analyze the results of the clusters and sub-clusters to produce insights on each customer segment relating to their characteristics and preferences |
| 5    | Conclusion                      | Summarize the insights to create customer profiles, and suggest a marketing strategy per segment based on the results                               |
| 6    | Recommendation                  | Provide recommendations for future studies on possible further improvements that could be made given the limitations of the current project         |

## Results
![dendrogram](https://github.com/user-attachments/assets/19319ef7-f4f5-4a99-a4ae-f97caa9c1071)

Whilst four clusters are feasible, three segments are selected instead, as the smallest fourth cluster contains only 30 customers, which may be too niche of a segment from a sales and marketing perspective.

![clusters](https://github.com/user-attachments/assets/4a08e432-8c98-4c2c-b2d2-417076f153a2)

`Cluster 1: The Affluent Traditionalists`  
`Subcluster 1 The Premier Traditionalists`:
These inviduals are characterized by a preference for premium goods, responsiveness to marketing campaigns, and a tendency for in-store shopping. This subcluster represents the premium and engaged segment emphasized by their high-end purchasing preferences and the significant expenditure on premium categories like wines and meats.

`Cluster 2: The Digital Economizers`  
`Subcluster 2 The Budget-Focused Families`:
These individuals are marked by budget-consciousness, digital engagement, and a lower response to marketing campaigns.
This subcluster embodies the value-conscious and digital-engager segment highlighted by their frequent web visits and balanced online and offline purchasing behavior suggest comfort with digital platforms, coupled with a focus on economical choices.  
`Subcluster 3 The Flexible Consumers`:
These indiduduals are characterized with their moderate spending and balanced approach to shopping and campaign responsiveness.
This subcluster captures the moderate and diverse shopper segment highlighted by their versatility in adapting to different shopping modes and responsiveness to various marketing campaigns.

The main clusters strategic roadmap for tailoring marketing and engagement efforts.
For `Main Cluster 1`, the focus should be on premium offerings, personalized services, and enhancing the in-store experience.
For `Main Cluster 2`, strategies should revolve around digital engagement, value-based promotions, and accommodating the needs of budget-conscious families.

## Acknowledgements
Special thanks to Prof. Christian Alis and his Data Mining and Wrangling 2 lectures.
