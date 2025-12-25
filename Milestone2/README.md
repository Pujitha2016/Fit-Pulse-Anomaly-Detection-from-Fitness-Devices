Milestone 2: Feature Extraction and Modeling

Milestone 2 focuses on transforming preprocessed fitness data into meaningful insights by extracting time-series features, modeling temporal trends, and identifying behavioral patterns. This milestone prepares the data for anomaly detection in later stages.

Feature Extraction:

Time-series features were automatically extracted from heart rate, steps, and sleep data using TSFresh. 
In addition, key statistical features such as mean, standard deviation, skewness, kurtosis, and frequency-based characteristics were computed. 
Relevant features were selected using variance thresholding to improve model effectiveness.

Trend Modeling:

Seasonal and temporal trends were modeled using Facebook Prophet. Forecasts were generated for heart rate, steps, and sleep data, along with confidence intervals. 
Deviations between actual and predicted values were analyzed to identify unusual behavior patterns.

Behavioral Pattern Clustering:

Unsupervised clustering techniques, including KMeans and DBSCAN, were applied to group similar behavioral patterns. 
PCA was used for dimensionality reduction and visualization. 
The resulting clusters help distinguish normal behavior from atypical patterns.

Milestone 2 successfully completed
