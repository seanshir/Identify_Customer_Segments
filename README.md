# Identify_Customer_Segments

## Project Motivation
In this project, I work with real-life data provided by Bertelsmann partners AZ Direct and Arvato Finance Solution. The data concerns a company that performs mail-order sales in Germany and the main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. The goal here is to utilize unsupervised learning techniques to group the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. 

## File Descriptions

- Identify_Customer_Segments.ipynb: python notebook with work done <br>
- Identify_Customer_Segments.html: html version of python notebook <br>
- Data_Dictionary.md: meanings of variables <br>

## Summary of the steps taken

There are two main sources of data: Demographics data of a general population and data of current customers. Comparing these datasets can help with targeting for a marketing campaign. <br>

• Data Preprocessing: Using Python Pandas, created a Cleaning Function to handle missing data and perform feature trimming, re-encoding, and engineering for the datasets. <br>

• Feature Transformation: Using Python sklearn, applied feature scaling and performed dimensionality reduction using PCA and interpreted the principal components. <br>

• Clustering: Using Python sklearn, applied K-Means clustering to general population data, and used a scree-plot to obtain the best number of clusters. <br>

• Finally, mapped the customer data to the created clusters and using some visualizations, the over-represented clusters in the customers data in comparison to general population were identified. These over-represented clusters can be targeted for future marketing campaigns. <br>

## Licensing, Acknowledgements:
Data provided by Bertelsmann SE & Co. KGaA, organized by Udacity.

