# Projects

## [Project 1: Body Mass Index (BMI): Application of predictive and descriptive methods](https://github.com/dayanacavalcante/Obesity-Estimate)
* Created a Linear Regression Model (MAPE = 14%) as an alternative to the formula that is used today, BMI = kg/m2, where kg is a person's weight in kilograms and m2 is their height in metres squared;
* Detected the groups of people at greatest health risk due to the level of obesity and the low (or zero) frequency of physical activity with clustering algorithms;
* Checked which algorithm had the best performance for classification of Body Mass Index (BMI): Logistic Regression Classifier (Accuracy = 70%), Decision Tree Classifier (Accuracy = 91%) and Random Forest Classifier (Accuracy = 93%);

![](/images/heatmap_2.png)


## [Project 2: Web API for Wine Classification](https://github.com/dayanacavalcante/ApiPython-WineClassify)
* Created Extra Trees Classifier Model (Accuracy = 99%) to be able to recognize whether the wine is red or white when it receives some features of the wine to the classifier;
* Created a Web API in Python using Flask;

![](/images/ConfusionMatrix.png)


## [Project 3: Anti-Spam Filter](https://github.com/dayanacavalcante/Anti-Spam-Filter)
* Created an anti-spam filter to classify emails in spam or non-spam with the Naive Bayes algorithm (Accuracy = 90%), using the NLTK library.

```
pipeline = Pipeline([
    ('bow', CountVectorizer(analyzer=ProcessText)),
    ('tfidf', TfidfTransformer()),
    ('classifier', MultinomialNB())
])
```

## [Project 4: Covid-19 Rio de Janeiro, Brazil](https://github.com/dayanacavalcante/Covid-19-RJ-Brazil-ARIMA)
* Applied stationary transformations and ARIMA model.

![](/images/TestStationarity_1.png)
