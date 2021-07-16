# Applying boosting & SVM with tailored kernels to image classification & movie review sentiment analysis tasks

•	Hand-created numerous kernel functions, in a vectorised form to maximise computational efficiency. These were applied via an SVC for image & sentiment classification.

•	Performances were compared to that of hand-crafted multi-class boosting algorithms (Adaboost & Gradient boosting) with decision trees, after tuning via 5-fold cross-validation.

•	Pre-processed review data (tokenising, removing stop words & lemmatising, as well as converting to n-grams & tf-idf format) and feature extraction on images (conversion to HoG & grey-scaled features). Found that cross-validation accuracy improved the most using standardised greyscale image data, and decided to flip training images as a form of feature engineering, double the training set size & reducing overfitting.

The movie review data can be found under "movie_review_train.csv" and image data within the "image_dataset" folder.

Final grade: First class (93%)
