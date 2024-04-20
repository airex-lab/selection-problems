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

## Problem 2 : Data Engineering Challenge (:TODO:)




Submission Requirements:
Submit the structured CSV file bbc_articles.csv.
Provide the Python code used to preprocess the data and train the text classification model.
Include a brief report or documentation summarizing the preprocessing steps, model architecture, and evaluation results.
Additional Notes:
Ensure that your code is well-commented and follows best practices for readability and maintainability.
Use libraries like pandas, scikit-learn, NLTK, SpaCy, or any other suitable libraries for data preprocessing and model training.
Experiment with different tokenization techniques, preprocessing steps, and machine learning algorithms to achieve the best performance.
Provide any necessary instructions or requirements for running your code, such as package dependencies or environment setup.
  - **Description**: You are provided with a zip file named data.zip, which contains a folder named BBC_articles. Inside this folder are text files named as "articleID_category", where "articleID" corresponds to the unique identifier of the article and "category" denotes the category of the article. Your task is to structure the data by creating a CSV file with appropriate columns. Then, you need to write code to read the CSV data, tokenize the text, and train a text classification model using NLP techniques..
  - **Task1 (Data Structuring)**: 
    - Unzip the data.zip file to access the BBC_articles folder.
    - Inside the BBC_articles folder, each text file is named as "articleID_category", where "articleID" is a unique identifier and "category" is the category of the article.
    - Create a CSV file named bbc_articles.csv with the following columns:
         - article_id: Unique identifier for each article.
         - text: Text content of the article.
         - category: Category of the article.
 - **Task 2 (Data Preprocessing for Model Training)**: 
        
     - Read the bbc_articles.csv file into a DataFrame using Python.
     - Tokenize the text data using a suitable tokenizer (e.g., NLTK, SpaCy).
     - Perform any necessary preprocessing steps such as lowercasing, removing stopwords, punctuation, etc.
     - Split the dataset into training and testing subsets.
     - Train a text classification model using any suitable algorithm (e.g., Naive Bayes, Logistic Regression, SVM, Neural Networks).
     - Evaluate the trained model's performance on the testing dataset using appropriate metrics (e.g., accuracy, precision, recall, F1-score).
     - Optionally, you can perform hyperparameter tuning to optimize the model's performance.
  - **Output**: A working prototype or detailed architecture proposal.
  - **Evaluation**: Efficiency, scalability, and innovation in the designed pipeline.

## Problem 3 : Machine Learning Engineering Challenge

  - **Goal**: Build a machine learning model and deploy it.
  - **Task**: Develop a machine learning model (image classification) based on provided data and deploy it as a simple web application or API.
  - **Output**: A GitHub repository with code, usage documentation and a live demo (could be a simple web page).
  - **Evaluation**: Performance of the model, code quality, and usability of the deployment.

  - **Data**: https://www.cs.toronto.edu/~kriz/cifar.html (use the CIFAR-10 version)


test