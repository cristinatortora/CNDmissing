# CNDmissing

The code in this directory reproduces the simulation design of the paper:

Model-based clustering and outlier detection with missing data (2021), Hung Tong and Cristina Tortora
Advances in Data Analysis and Classification.


Abstract: The use of the multivariate contaminated normal (MCN) distribution in model-based clustering is recommended to cluster data characterized by mild outliers, the model can at the same time detect outliers automatically and produce robust parameter estimates in each cluster. However, one of the limitations of this approach is that it requires complete data, i.e. the MCN cannot be used directly on data with missing values.  In this paper, we develop a framework for fitting a mixture of MCN distributions to incomplete data sets, i.e. data sets with some values missing at random. Parameter estimation is obtained using the expectation-conditional maximization algorithm, a variant of the expectation-maximization algorithm in which the traditional maximization steps are instead replaced by simpler conditional maximization steps. We perform a simulation study to compare the results of our model to a mixture of multivariate normal and Student's t distributions for incomplete data. The simulation also includes a study on the effect of the percentage of missing data on the performance of the three algorithms. The model is then applied to the Automobile data set (UCI machine learning repository). The results show that, while the Student's t distribution give similar classification performance, the MCN works better in detecting outliers with a lower false positive rate of outlier detection. The performance of all the techniques decreases linearly as the percentage of missing values increases. 
