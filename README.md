# Principal-Component-Analysis

This work consists in the study of Principal Component Analysis from a theoretical and practical point of view. It is composed of 3 parts. 

# 1. Theory: Consistency of PCA

In the case of a centered multinomial Gaussian distribution, we find upper bounds for the estimation error between the eigenvectors and eigenvalues of the sample covariance matrix and the real covariance matrix.
Therefore, we prove the consistency of the PCA algorithm for a fixed covariance matrix. The results and proofs can be found in the report.

# 2. Simulations

We simulate multiple centered Gaussian distributions and measure the estimation errors of PCA in order to confirm and complete the results found in theory. The code related to this part can be found in the Jupyter notebook PCA-Simulations, and the results are described in the report. 

# 3. Application: Anomaly detection

In a simple application (detection of anomalous regions of a satellite image), we propose various PCA-based approaches for detecting outliers (Mahalanobis distance, k-means, logistic regression). Code can be found in PCA-Anomaly-detection.ipynb.

