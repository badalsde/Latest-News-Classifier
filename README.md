# Latest-News-Classifier

Latest News articles categorization is a supervised learning approach in which news articles are assigned category labels based on likelihood demonstrated by a training set of labeled articles. A system for automatic categorization of news articles into a standard set of categories has been implemented. The proposed work will use Term Frequency–Inverse Document Frequency (TF-IDF) term weighting scheme for optimization of classification techniques to get more optimized results and use six supervised learning approaches, i.e., 
* Gradient Boosting
* k Nearest Neighbor(kNN)
* Logistic Regression
* Multinomial Naive Bayes
* Random Forest
* Support Vector Machines(SVM)

 and compare the performances of all classifiers. Each news document is preprocessed and transformed into a term-document matrix. After preprocessing and transforming each news article into a vector of weights, TF-IDF term weighting scheme was used for weighting the word. TF-IDF weighted the words calculating the number of words that appear in a document. An unknown news item is also transformed into a vector of keyword weights, and then categorized into suitable categories such as Sports, Business,Politics, Entertainment and Technology. The system purposed in research work was trained on the collection of approximately 100 categorized news articles extracted from the various newspaper websites and tested on a different set of 20 randomly extracted news items from the same sources.
