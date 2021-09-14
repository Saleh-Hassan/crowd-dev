# `crowd-dev`

This repository contains the code for `NLP analysis of tweets`. I have tried following three approaches:

- TF-IDF vectorization of tweets followed by classifcation of tweets using non DL models(`LogisticRegression`, `SupportVectorClassifier`, `XGBoostClassifier` etc.)
- Fine-tuning of pre-trained DistilBERT model on disaster tweet classification task.
- Zero-shot classification on tweet classification task. This appraoch doesn't require any training labels.

The tags in `predicted_test.csv` are generated using `DistilBERT`. All the models are trained on [nlp with disaster tweets dataset](https://www.kaggle.com/c/nlp-getting-started "nlp with disaster tweets dataset"). 

## Install 

To install dependencies:

```sh
pip install -r requirements.txt
```
