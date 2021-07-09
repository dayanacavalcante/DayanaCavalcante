# Projects


## [Project 1: Obesity Level Estimate Case Study: Application of predictive and descriptive methods](https://github.com/dayanacavalcante/Obesity-Estimate)
* Created a Regression model (r2_score = 0.95) to check which variables based on eating habits and physical condition most influence the prediction of obesity levels;
* Detected a group of people with possible high health risk due to the highest level of obesity and low (or none) frequency of physical activity with clustering algorithms: K-means (silhouette_score = 0.49), Hierarchical (silhouette_score = 0.47), and DBSCAN (silhouette_score = 1.0);
* Checked which algorithm had the best performance for obesity levels classifier: Decision Tree (Accuracy = 93.2%), Random Forest (Accuracy = 93.1%), Logistic Regression (Accuracy = 84.8%), Support Vector Classifier (Accuracy = 83.1%), K-nearest neighbors (Accuracy = 77%), and Naive Bayes (Accuracy = 49.1%);

![](/images/heatmap.png)


## [Project 2: MRI Recognition with Keras and Tensorflow](https://github.com/dayanacavalcante/MRI-Recognition-with-Keras-and-Tensorflow)
* Created a CNN using Keras + Tensorflow to classify MRI;

```
Model: "sequential_1"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_2 (Conv2D)            (None, 99, 99, 64)        832       
_________________________________________________________________
max_pooling2d_2 (MaxPooling2 (None, 49, 49, 64)        0         
_________________________________________________________________
dropout_3 (Dropout)          (None, 49, 49, 64)        0         
_________________________________________________________________
conv2d_3 (Conv2D)            (None, 48, 48, 128)       32896     
_________________________________________________________________
max_pooling2d_3 (MaxPooling2 (None, 24, 24, 128)       0         
_________________________________________________________________
dropout_4 (Dropout)          (None, 24, 24, 128)       0         
_________________________________________________________________
flatten_1 (Flatten)          (None, 73728)             0         
_________________________________________________________________
dense_2 (Dense)              (None, 256)               18874624  
_________________________________________________________________
dropout_5 (Dropout)          (None, 256)               0         
_________________________________________________________________
dense_3 (Dense)              (None, 4)                 1028      
=================================================================
Total params: 18,909,380
Trainable params: 18,909,380
Non-trainable params: 0
_________________________________________________________________
```


## [Project 3: Web API for Wine Classification](https://github.com/dayanacavalcante/ApiPython-WineClassify)
* Created Extra Trees Classifier Model (Accuracy = 99%) to be able to recognize whether the wine is red or white when it receives some features of the wine to the classifier;
* Created a Web API in Python using Flask;

![](/images/ConfusionMatrix.png)


## [Project 4: Unsupervised learning for Country Grouping](https://github.com/dayanacavalcante/UnsupervisedLearningForCountryGrouping)
* Use of Data Science resources to choose countries that most need help from HELP Internacional, according to income and Per Capita GDP;

![](/images/scatterplot.png)


## [Project 5: Anti-Spam Filter](https://github.com/dayanacavalcante/Anti-Spam-Filter)
* Created an anti-spam filter to classify emails in spam or non-spam with the Naive Bayes algorithm (Accuracy = 90%), using the NLTK library.

```
pipeline = Pipeline([
    ('bow', CountVectorizer(analyzer=ProcessText)),
    ('tfidf', TfidfTransformer()),
    ('classifier', MultinomialNB())
])
```


## [Project 6: Covid-19 Rio de Janeiro, Brazil](https://github.com/dayanacavalcante/Covid-19-RJ-Brazil-ARIMA)
* Applied stationary transformations and ARIMA model.

![](/images/TestStationarity_1.png)
