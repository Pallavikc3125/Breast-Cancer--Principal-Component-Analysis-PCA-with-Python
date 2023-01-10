# Principal Component Analysis with Python

To use principal component analysis (PCA) on the breast cancer Wisconsin dataset, you will first need to import the PCA class from scikit-learn's decomposition module. You can then create an instance of the PCA class, passing the desired number of components as an argument.

To apply PCA to the data, you can call the fit_transform method of the PCA object and pass in the features as an argument. This will fit the PCA model to the data and transform the features into the principal component space.

The transformed data is stored in the X_pca array, which has the same number of samples as X but a reduced number of features (the number of features is equal to the number of components specified in the PCA object). You can access the explained variance ratio of the principal components using the explained_variance_ratio_ attribute of the PCA object.

Keep in mind that PCA is an unsupervised method, so you will not use the labels (y) in the transformation process. Instead, you will use the features (X) to fit the model and generate the principal components. You can then use the transformed data (X_pca) for downstream tasks such as visualization or further analysis.

Libraries Used:
* pandas
* numpy
* matplotlib.pyplot

To understand the value of using PCA for data visualization, this post goes over a basic visualization of the breast_cancer dataset after applying PCA.
