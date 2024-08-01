# 📊 Text Mining and Machine Learning Project: Exploring Customer Satisfaction Dimensions 

## 🌟 Overview

This project focuses on analyzing Ryanair customer reviews to extract key topics and classify customer satisfaction using advanced text mining and machine learning techniques. The dataset includes 2,250 reviews from 2012 to the present, providing a rich source of customer feedback for detailed analysis.

## 📂 Project Structure

The project is divided into three Jupyter notebooks, each addressing different aspects of the analysis:

### 1. 🗂️ Topic Extraction and Sentiment Analysis

**Objective:** Extract and analyze the main topics from Ryanair reviews.

- **Text Mining Preprocessing**: Clean and preprocess the dataset, focusing on extracting and preparing nouns and adjectives for further analysis.
- **Latent Dirichlet Allocation (LDA)**: Identify and extract key topics from the reviews.
- **Bayesian Analysis**: Estimate sentiment scores for adjectives, associating them with the extracted topics.
- **Sentiment Score Calculation**: Normalize sentiment scores (positive or negative) for each topic per review.
- **Logistic Regression**: Evaluate the importance of each topic as a feature and assess the effectiveness of the classifier with these enhanced features.

### 2. 📈 Pattern Analysis and Application

**Objective:** Apply the extracted topics and sentiment scores to identify patterns and relationships.

- **Pattern Frequency Analysis**: Explore correlations between flight characteristics (e.g., punctuality, comfort, customer origin, destination, flight reason) and the sentiment scores of the extracted topics.
- **Visualization and Interpretation**: Provide visual representations and interpretations of how different topics and sentiments relate to various aspects of the flight experience.

### 3. 🖥️ Model Application and Interface

**Objective:** Provide a user-friendly interface to test and interact with the machine learning model.

- **Interactive Interface**: A simple web-based interface to input new reviews, apply the trained model, and receive predictions on customer satisfaction and topic relevance.
- **Model Testing**: Test and validate the model's performance with new data.

## 📥 Dataset

The analysis utilizes the dataset available on Kaggle:

- **Dataset URL**: [Ryanair Reviews & Ratings](https://www.kaggle.com/datasets/cristaliss/ryanair-reviews-ratings)

This dataset contains reviews and ratings from Ryanair customers, providing a foundation for extracting insights and developing the model.

## 🛠️ Requirements

To run the notebooks and interact with the model, you will need the following Python libraries:

- `pandas`
- `numpy`
- `sklearn`
- `nltk`
- `gensim`
- `matplotlib`
- `seaborn`
- `tkinter` (for the interface)

## 🚀 Usage

### Run the Jupyter Notebooks:

1. **Start with the first notebook** to preprocess the data, extract topics using LDA, perform sentiment analysis with Bayesian methods, and evaluate the classifier with logistic regression.
2. **Use the second notebook** to analyze patterns and relationships between topics and flight characteristics.
3. **Test the final model** using the third notebook's web interface.

### Interactive Testing:

- Launch the app interface from the third notebook to input new reviews and get predictions on customer satisfaction and topic relevance.

## 🤝 Contribution

Feel free to fork the repository and contribute by improving the analysis, enhancing the model, or suggesting new features.

## 📝 License

This project is licensed under the [Apache 2.0 License](LICENSE). See the LICENSE file for more details.

## 📚 For More Information

- Read my presentation and documentation.
- For any questions or issues, please open an issue on the repository or contact the project maintainer.

Happy analyzing! 😊
