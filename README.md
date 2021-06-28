# Projects


## [Project 1: Body Mass Index (BMI): Application of predictive and descriptive methods](https://github.com/dayanacavalcante/Obesity-Estimate)
* Created a Regression model (r2_score = 0.95) to check which variables based on food habits and physical condition most influence the prediction of BMI;
* Detected the groups of people at greatest health risk due to the level of obesity and the low (or zero) frequency of physical activity with clustering algorithms: K-means (silhouette_score = 0.5), Hierarchical (silhouette_score = 0.5) and DBSCAN (silhouette_score = 1.0);
* Checked which algorithm had the best performance for classification of BMI: Decision Tree (Accuracy = 93.2%), Random Forest (Accuracy = 93.1%), Logistic Regression (Accuracy = 84.8%), Support Vector Classifier (Accuracy = 83.1%), K-nearest neighbors (Accuracy = 77%), and Naive Bayes (Accuracy = 49.1%);
* Warning: the project is currently under review and the code can be accessed from the develop/ScaledData branch;

![](/images/heatmap_2.png)


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


## [Project 4: Anti-Spam Filter](https://github.com/dayanacavalcante/Anti-Spam-Filter)
* Created an anti-spam filter to classify emails in spam or non-spam with the Naive Bayes algorithm (Accuracy = 90%), using the NLTK library.

```
pipeline = Pipeline([
    ('bow', CountVectorizer(analyzer=ProcessText)),
    ('tfidf', TfidfTransformer()),
    ('classifier', MultinomialNB())
])
```


## [Project 5: Covid-19 Rio de Janeiro, Brazil](https://github.com/dayanacavalcante/Covid-19-RJ-Brazil-ARIMA)
* Applied stationary transformations and ARIMA model.

![](/images/TestStationarity_1.png)
