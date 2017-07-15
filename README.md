# AI month in AS, Taiwan
A brief talk about machine learning in Python

# supervised learning (1hr)
## Classification and Regression
0. Linear regression
	- which one would be the best classifer while having many possibility to perfectly discriminate data?
	- maximal margin => SVM
	
1. SVM
	- Mathematical formulation
	- relation to logistic regression in view of loss function
	- kernel trick (linear, poly, rbf)

2. RandomForest
	- 原理
	- Decision Tree
	- Pros and Cons

3. XGBoost
	- 原理
	- the difference with GBDT
	- Gradient Boosting Method
	- Ensemble of a series of randomforests with gradient boosting

# unsupervised learning (1hr)
1. Dimension reduction
	- why we need dimension reduction?
	- how to find out the principal components from observed data?

2. 說明 PCA 原理
	- (1) linear combination of original features, (2) explain the most variance in that
		- http://web.ntpu.edu.tw/~ccw/statmath/M_pca.pdf
	- 什麼是 explained variance: 投影到某一軸, data variance 能夠被表達多少
		- https://stats.stackexchange.com/questions/22569/pca-and-proportion-of-variance-explained
		- https://stats.stackexchange.com/questions/254592/calculating-pca-variance-explained/254598
		- an example to verify
	- PCA example and visualization

3. Other feature selection method 
	- Lasso regression

4. Clustering
	- Kmeans clustering
	- Minibatch Kmeans clustering
	- GMM (Gaussian Mixed Model)
	- Kernel Approximation
