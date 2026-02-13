# Tweeter-Sentiment-Prediction-Model



#### \# Twitter Sentiment Prediction Model

#### 

#### A machine learning model for predicting sentiment (positive/negative) from Twitter text.

#### 

#### \## Model Details

#### \- \*\*File Size\*\*: 3.69 MB

#### \- \*\*Model Type\*\*: Logistic Regression (or your model type)

#### \- \*\*Vectorizer\*\*: TF-IDF

#### 

#### \## Files

#### \- `models/twitter\_sentiment\_model.pkl` - Trained sentiment prediction model

#### 

#### \## Usage

#### ```python

#### import pickle

#### 

#### \# Load model

#### with open('models/twitter\_sentiment\_model.pkl', 'rb') as f:

#### &nbsp;   model = pickle.load(f)

#### 

#### \# Make prediction (ensure you have the vectorizer too)

#### \# prediction = model.predict(vectorized\_text)

#### ```

#### 

#### \## Requirements

#### \- scikit-learn

#### \- pandas

#### \- numpy

