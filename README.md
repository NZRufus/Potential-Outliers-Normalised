# Potential-Outliers-Normalised
Normalising data prior to identify outliers using Isolation Forest, kNN and Principal Component Analysis (PCA)

Data was collected and previously extracted and cleaned from internal data sources. 

A lot of the variables were non-Gaussian and it was found that data when transformed by yeo-johnson to make more normal and enabling better results (even though PCA and Isolation Forest don't necessarily need Gaussian distribution).

Impacts of each variables on detection of outliers were analysed using the different techniques as well as potentially identify outliers. 

The three methods had good agreement with outliers with there being 78% of outliers being in all three measures when using 5% of samples having outliers and 69% when 10% of outliers. There was better agreement between PCA and Isolation Forest than with kNN. 
