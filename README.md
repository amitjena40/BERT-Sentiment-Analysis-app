# BERT-Sentiment-Analysis-app

Heavily inspired from this repository: https://github.com/abhishekkrthakur/bert-sentiment

Dataset: https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

BERT (based-uncased) pre-trained model: https://www.kaggle.com/abhishek/bert-base-uncased

Run the file train.py to train the bert-based-uncased model. The weights will be stored as model.bin file.

To run the flask app after training the model, run app.py file.

The code was tested on Google Colab with VSCode, using ngrok. Flask-ngrok library is required to connect to localhost server when using the flask app.
