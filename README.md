# Repo structure
This repository trains a model to detect sarcastic headlines. You can test it with:
* `demo.ipynb` - you can input a headline, and the code tells you if it is sarcastic or not, and visualises what features of the headline lead to that decision.

The following files are for the training of the model:
* `sarcasm_detection.ipynb` - code that trains the model and tests the explainability
* `clf.sav` - pretrained Logistic Regression model
* `tfidf.sav` - pretrained TfIdf vectorization 
* `transformers.h5` - pretrained transformers model with code reused from https://www.kaggle.com/code/quadeer15sh/transformers-for-text-classification 

# Data
Data source and attribution:
* https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection

# Models
The models are stored in the repository in `clf.sav` and `tfidf.sav`.

# References
* https://marcotcr.github.io/lime/tutorials/Lime%20-%20basic%20usage%2C%20two%20class%20case.html
* https://www.kaggle.com/code/prashant111/explain-your-model-predictions-with-lime
* https://scikit-learn.org/stable/model_persistence.html
* https://machinelearningmastery.com/save-load-machine-learning-models-python-scikit-learn/
