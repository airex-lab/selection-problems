# Problems

## Instructions

  - Solve the problem assigned to you among the below listed problems and upload all your code and artefacts in a github repository and share its link. Make sure the repository is public.

## Problem 1 : Data Science Challenge

  - **Goal**: Predictive modeling and data visualization.
  - **Task**: 
    - Visualize the relation between features (you can design your own new features based on the given data)
	- Develop an ML model which, given the name of a director, predicts the release year of his next movie along with its probable genres
  - **Output**: A GitHub repository with code, report or presentation that includes insights, methodologies, and conclusions.
  - **Evaluation**: Accuracy of predictions, creativity in approach, clarity of presentation, and depth of insights.

  - **Data**: **Movie Metadata** ([./data/p1_movie_metadata.csv](./data/p1_movie_metadata.csv))

## Problem 2 : Data Engineering Challenge 



  - **Description**: You are provided with a zip file named [data.zip](./data/data.zip), which contains a folder named BBC_articles. Inside this folder are text files named as "articleID_category", where "articleID" corresponds to the unique identifier of the article and "category" denotes the category of the article. Your task is to structure the data by creating a CSV file with appropriate columns. Then, you need to write code to read the CSV data, tokenize the text, and prepare the dataset to have numerical features using vectorization. Goal is to clean and prepare the dataset so that in can be trained using NLP-classification techniques.
  - **Task1 (Data Structuring)**: 
    - Unzip the data.zip file to access the BBC_articles folder.
    - Inside the BBC_articles folder, each text file is named as "articleID_category", where "articleID" is a unique identifier and "category" is the category of the article.
    - Create a CSV file named bbc_articles.csv with the following columns:
         - article_id: Unique identifier for each article.
         - text: Text content of the article.
         - category: Category of the article.
 - **Task 2 (Data Preprocessing for Model Training)**: 
        
     - Read the bbc_articles.csv file into a DataFrame using Python.
     - Tokenize the text data using a suitable tokenizer (e.g., NLTK, SpaCy)(Even better if you perform custom tokenization.)
     - Perform any necessary preprocessing steps such as lowercasing, removing stopwords, punctuation, etc.
     - Make a new csv file with numerical features and given labels.
     - Note: Features are typically derived through text vectorization    techniques such as:
        - Bag-of-Words (BoW): Each feature represents the count or frequency of each word in the document.
        - TF-IDF (Term Frequency-Inverse Document Frequency): Each feature represents the TF-IDF score of each word in the document.
        - Word Embeddings: Each feature represents the vector representation of each word in the document (e.g., Word2Vec, GloVe). 
     - You are free to choose how you vectorize to get the feature   
  - **Submission Requirements**:
  
     - Submit the structured CSV file bbc_articles.csv.
     - Submit final datset as a CSV file containing numerical features.
        >(name it as vectorized_dataset.csv).
     - Provide the Python code used to preprocess the data and vectorize ot for the text classification.
     - Include a brief report or documentation summarizing the preprocessing steps, and what methods you adopted for featurization.
     - Additional Notes:
        - Ensure that your code is well-commented and follows best practices for readability and maintainability.
    
        - Provide any necessary instructions or requirements for running your code, such as package dependencies or environment setup.
     
## Problem 3 : Machine Learning Engineering Challenge

  - **Goal**: Build a machine learning model and deploy it.
  - **Task**: Develop a machine learning model (image classification) based on provided data and deploy it as a simple web application or API.
  - **Output**: A GitHub repository with code, usage documentation and a live demo (could be a simple web page).
  - **Evaluation**: Performance of the model, code quality, and usability of the deployment.

  - **Data**: https://www.cs.toronto.edu/~kriz/cifar.html (use the CIFAR-10 version)


