Principal component analysis is a multivariate statistical technique. Its main objective is to reduce the dimensionality of a data set while preserving as much information as possible. This is achieved by transforming the original data into a new set of variables, called principal components, which are linear combinations of the original variables. In general, with PCA we go from N to p variables, where P<N.

PCA is not a machine learning technique per se, but a statistical and data analysis technique that is commonly used as a preliminary step in many machine learning applications. the overall idea is to reduce the dimensionality of the data and find the most important relationships or patterns between variables in a data set. This technique focuses on exploratory data analysis and data simplification, rather than on building predictive models. However, PCA is widely used in the context of machine learning and machine learning. It is used before applying machine learning algorithms to reduce the dimensionality of data, eliminate multicollinearity between variables or to visualize high-dimensional data effectively.

## EFA vs PCA

Exploratory Factor Analysis (EFA) and Principal Component Analysis (PCA) are two related techniques, but have different objectives and approaches in multivariate data analysis.

Let's see the differences:

Regarding objective:

- PCA: The main objective of PCA is to reduce the dimensionality of the data while preserving as much variance in the data as possible. PCA seeks to find linear combinations of the original variables (called principal components) that capture the total variance of the data.
- EFA: The main objective of EFA is to identify underlying or latent structures in the data, i.e., unobserved relationships between the original variables. EFA is used to explore the relationships between variables and to discover underlying factors that may explain the correlations between them.

Regarding Assumptions:

- PCA: PCA makes no assumptions about the existence of latent or causal factors between variables. It is based on the covariance or correlation matrix of the observed variables.
- EFA: EFA starts from the assumption that observed variables are related to each other due to unobserved latent factors. EFA attempts to decompose correlations between variables into underlying factors and single errors.

Regarding to interpretation:

- PCA: The principal components of PCA have no direct interpretation in terms of latent or causal factors. They represent linear combinations of the original variables that maximize variance.
- EFA: The factors extracted in EFA are interpreted as latent constructs or underlying factors that may have theoretical or practical significance. These factors are used to explain the observed correlations between variables.

Regarding to application:

- PCA: It is commonly used in data analysis, dimensionality reduction and data compression. Its main focus is to simplify the data while keeping the important information.
- EFA: It is used in psychometric research, psychology, social sciences and in any context in which one seeks to identify underlying factors or latent dimensions in a data set.

## Basic PCA methodology

1. Standardize the data: For PCA to work effectively, it is common to standardize or normalize the data, ensuring that all variables have the same scale.
2. Calculation of the covariance matrix: The covariance matrix of the original variables is calculated to understand how they are related to each other.
3. Calculation of the principal components: Next, the principal components, which are linear combinations of the original variables, are calculated. These components are selected to capture as much variance as possible in the data. The first principal component captures the largest variance, the second principal component captures the next largest variance, and so on.
4. Dimensionality reduction: Once the principal components are calculated, you can select a smaller number of them to represent the data. This reduces the dimensionality of the data, which can be useful for visualizing the data or for performing further analysis more efficiently.
5. Interpretation: Principal components can be interpreted to understand which original variables contribute most to each principal component. This can help identify patterns or relationships in the data.
