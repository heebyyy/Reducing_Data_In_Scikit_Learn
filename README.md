# Reducing_Data_In_Scikit_Learn

The built in breast cancer dataset in sklearn is used and a classification model is built using all of its features, the dimension is then reduced using the scikit learn libraries and these models are compared against each other. 

The King county Housing Prices data set is used to build a regression model where all it features are used before the dimension is then reduced and the ols model isused withthe reduced features. The results arethen compared, this dataset can be found <a href=https://www.kaggle.com/harlfoxem/housesalesprediction target='_blank'>here</a>

The boston housing dataset,an inbuilt dataset into sklearn is also used topredict home prices using linear regression. This particular dataset isusefulin describing how principal component analysis works.

The iris dataset, also one of the built in datasets in sklearn is used for linear discriminant analysis. The total contains 150 recors with three class. There are 50 records for each class.

We also used the manifold learning for dimensionality reduction, allthe techniques used rely on the manifold hypothesis which basically state that in the real world, complex data with high dimensional space has a simpler manifold in a lowe dimension. Manifold techniques can be used to unroll and smoothen out data in higher dimension to simpler data in lower dimension. A few implementationof manifold learingwas used, these include, multi dimensional scaling, isomap, spectral embedding etc. The techniques werefirst applied on a much simple dataset which is the hand written digits dataset built into scikit learn, and the olivetti dataset that which is more complex is later used