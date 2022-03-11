# Arabic-Dialect-Web-App
## Web application for classifying arabic dialects
The whole application was made on google colab so feel free to change the save & load paths.
There are four notebooks:
  1) request handler.ipynb: responsible for fetching dataset from API using id.
  2) data_preprocessing.ipynb: responsible for processing raw string, data analysis, create tf-idf vectorizer, create padding tokenizer, create word2vec model and embedding matrix.
  3) Model_training.ipynb: responsible for training 2 machine learning models and on deep neural networks model.
  4) arabic_dialect_app.ipynb: responsible for creating flask web application deploying with ngrok.

For test purpose run arabic_dialect_app notebook, make sure the following is included:
  1) deep neural model: https://drive.google.com/drive/folders/1egFUP2UHgxpFxJvXiFRePmOTP-pnqVMA?usp=sharing
  2) padding tokenizer: https://drive.google.com/file/d/1-3lFBPoQ2tQD80gKz3mnt4dUfyTSzk0i/view?usp=sharing
  3) tfidf vectorizer: https://drive.google.com/file/d/1-2Kwo-lE-O04BZ7zLjTUw4RskzFWuoV4/view?usp=sharing
  4) sgd calssifier for tfidf vectorization: included in repo with name sgd_tfidf
  5) label encoder: included in repo
 
 For training:
  1) Download the ids dataset
  2) Don't forget to change paths
  3) Run fetch notebook to retrieve text dataset
  4) Run processing function in data_preprocessing notebook, make sure to comment function after done
  5) Run Model_training notebook
