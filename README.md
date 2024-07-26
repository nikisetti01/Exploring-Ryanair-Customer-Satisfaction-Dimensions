## Text Mining and Machine Learning Project: Expploring Customer Satisfaction Dimensions 
# Overview

This project focuses on analyzing Ryanair customer reviews to extract key topics and classify customer satisfaction using advanced text mining and machine learning techniques. The dataset includes 2,250 reviews from 2012 to the present, providing a rich source of customer feedback for detailed analysis.
Project Structure

The project is divided into three Jupyter notebooks, each addressing different aspects of the analysis:
1. Topic Extraction and Sentiment Analysis

Objective: Extract and analyze the main topics from Ryanair reviews.

    Text Mining Preprocessing: The dataset is cleaned and preprocessed, focusing on extracting and preparing nouns and adjectives for further analysis.
    Latent Dirichlet Allocation (LDA): Applied to the preprocessed nouns to identify and extract key topics from the reviews.
    Bayesian Analysis: Used to estimate sentiment scores for adjectives, which are then associated with the extracted topics.
    Sentiment Score Calculation: Sentiment scores (positive or negative) are normalized for each topic per review.
    Logistic Regression: Employed to evaluate the importance of each topic as a feature and assess the effectiveness of the classifier with these enhanced features.

2. Pattern Analysis and Application

Objective: Apply the extracted topics and sentiment scores to identify patterns and relationships.

    Pattern Frequency Analysis: Explores correlations between flight characteristics (e.g., punctuality, comfort, Customer Origin, Destination, Flight reason) and the sentiment scores of the extracted topics.
    Visualization and Interpretation: Provides visual representations and interpretations of how different topics and sentiments are related to various aspects of the flight experience.

3. Model Application and Interface

Objective: Provide a user-friendly interface to test and interact with the machine learning model.

    Interactive Interface: A simple web-based interface to input new reviews, apply the trained model, and receive predictions on customer satisfaction and topic relevance.
    Model Testing: Allows for testing and validation of the model's performance with new data.

Dataset

The analysis utilizes the dataset available on Kaggle:

    Dataset URL: https://www.kaggle.com/datasets/cristaliss/ryanair-reviews-ratings

This dataset contains reviews and ratings from Ryanair customers, providing a foundation for extracting insights and developing the model.
Requirements

To run the notebooks and interact with the model, you will need the following Python libraries:

    pandas
    numpy
    sklearn
    nltk
    gensim
    matplotlib
    seaborn
    tkinter ( for the interface)

Usage

    Run the Jupyter Notebooks:
        Start with the first notebook to preprocess the data, extract topics using LDA, perform sentiment analysis with Bayesian methods, and evaluate the classifier with logistic regression.
        Use the second notebook to analyze patterns and relationships between topics and flight characteristics.
        Test the final model using the third notebook's web interface.

    Interactive Testing:
        Launch the App interface from the third notebook to input new reviews and get predictions on customer satisfaction and topic relevance.

Contribution

Feel free to fork the repository and contribute by improving the analysis, enhancing the model, or suggesting new features.
License

This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.
For more information Read my presentation and documentation. 
For any questions or issues, please open an issue on the repository or contact the project maintainer.
