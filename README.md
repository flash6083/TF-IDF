# **Recommender system based on TF_IDF text vectorization implemented in Tensorflow**
TF-IDF Based Text Recommender Model
This repository contains a machine learning model that uses TF-IDF to recommends movies to users based on their input queries.

The model is built using Python and the following libraries:

- Pandas
- Scikit-learn
- json

## **Getting Started**
To use the model, follow these steps:

1. Clone this repository to your local machine
2. Install the required libraries (Pandas, Scikit-learn, json)
3. Run the notebook script to train the model on your dataset
4. Once the model is trained, you can use the ```movie_recommend()``` function to generate recommendations based on user queries.
## ***Model Details***
The TF-IDF (Term Frequency - Inverse Document Frequency) model is a popular information retrieval technique that assigns a numerical value to each word in a document, based on its frequency in the document and its rarity in the entire corpus of documents.

The TF-IDF values for each word in the document are then used to calculate a similarity score between the query and each document in the corpus. The documents with the highest similarity scores are then recommended to the user.

### **Dataset**
Kaggle Dataset Link - [TMDB 5000](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

The model requires a dataset of text documents to be trained on. The dataset should be in CSV format, with each row representing a single document and containing the following columns:

* id - a unique identifier for the movie
* title - the title of the movie
* genres/keywords - the genres associated with the movie
## **Performance**
The performance of the model can be evaluated using standard metrics such as precision, recall, and F1-score.

## **Contributors**
This model was developed by Sayak Bhattacharya. Contributions are welcome - feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvement.
