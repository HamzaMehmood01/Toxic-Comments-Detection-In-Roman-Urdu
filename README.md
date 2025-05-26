# Toxic Comment Classification Project

This project focuses on building and evaluating machine learning models to classify comments as either toxic or non-toxic. The goal is to identify harmful online content using natural language processing techniques.

## Project Overview

In this project, I implemented and compared the performance of three classification algorithms:

-   **Multinomial Naive Bayes:** A probabilistic algorithm often used for text classification.
-   **Decision Tree:** A tree-based model that makes decisions by splitting data based on features.
-   **Support Vector Machine (SVM) with RBF Kernel:** A powerful algorithm that finds an optimal hyperplane to separate data points in a high-dimensional space.

## Data

The project utilizes a dataset containing comments labeled as toxic or non-toxic. Data preprocessing steps included:

-   Handling missing values
-   Lowercasing and stripping whitespace
-   Encoding labels
-   Removing stop words
-   Removing duplicate entries
-   Normalizing comment lengths using StandardScaler
-   Outlier removal based on comment length using the Interquartile Range (IQR) method

## Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) vectorization was used to convert the text data into numerical features, capturing the importance of words in the comments.

## Model Training and Evaluation

The dataset was split into training and testing sets to train and evaluate the models. The performance of each model was assessed using the following metrics:

-   Accuracy
-   Precision
-   Recall
-   F1 Score

Confusion matrices were also generated to visualize the performance of the classifiers.

## Key Findings

[Summarize the key findings from your model evaluation. For example, mention which model performed best and why, or any interesting insights from the confusion matrices.]

## Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   NLTK

## How to Run the Code

[Briefly explain how someone can run your code if it's hosted on a platform like GitHub. For example, mention cloning the repository and running the notebook in Google Colab.]

## Acknowledgements

[Optional: Thank any resources, datasets, or libraries you used.]

## Contact

Feel free to connect with me on LinkedIn to discuss this project or other interesting data science and machine learning topics!

[Your LinkedIn Profile URL]
