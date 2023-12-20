# Analysis-of-CDC-s-Health-Data
Analysis of CDC's Health Data and UX Improvement Experiments

Part I: Analysis of CDC's 500 Cities Project Data

Overview
The project began with the analysis of the 'cities.csv' dataset from the CDC's 500 Cities Project. This dataset included information on the prevalence of various health conditions in 123 US cities.

Objectives & Methods
The project was structured into several analytical phases:

Data Preparation: The cities.csv dataset was loaded in R, the 'City' column was dropped, and other columns were renamed to simpler terms like 'arthritis', 'kidney_disease', 'copd', etc.
Principal Component Analysis (PCA): PCA was applied to the dataset with variables centered and scaled. This aimed to reduce dimensionality and identify underlying patterns.
Variance Explained by Principal Components: The proportion of variance explained by the principal components and their cumulative proportion were computed and plotted.
Effective Dimensionality Determination: Based on the cumulative variance plot, the effective dimensionality of the dataset was assessed to understand if the observations were concentrated in a smaller subspace.
Correlation Matrix Computation: The correlation matrix for the variables was computed and examined to evaluate if PCA's success in reducing dimensionality was anticipated.
Biplot for Principal Components: A biplot for the first two principal components was produced and interpreted to understand the relationships between variables and principal components.
Part II: Analysis of UX Improvement Experiments

Overview
The project then shifted to analyzing the 'experiments.csv' file, which contained p-values from 100 UX experiments conducted by a web company.

Objectives & Methods
This section involved:

Data Loading: The experiments.csv dataset, containing p-values from UX experiments, was loaded in R.
Significance Level Analysis: The number of experiments that generated a statistically significant UX improvement at the α = 0.10 level was determined.
Family-Wise Error Rate (FWER) Calculation: The effective FWER incurred by not accounting for multiple testing was calculated, assuming independence of the statistical tests.
Benjamini-Hochberg Method Application: The Benjamini-Hochberg method was applied to control the False Discovery Rate (FDR) at q = 0.10, identifying experiments that likely resulted in UX improvement.
Deliverables

The project resulted in a detailed report combining findings from both parts. The first part provided insights into public health data through statistical techniques like PCA, enhancing the understanding of health conditions across different cities. The second part addressed the challenges of multiple hypothesis testing in the context of UX experiments, demonstrating the practical application of statistical methods in a business setting. The project showcased a robust analytical approach, effectively merging data analysis skills with real-world applications.
