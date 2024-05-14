# Fake News Detection Project

## Introduction
This project aims to detect fake news using machine learning algorithms. The dataset used consists of two files: fake.csv and true.csv, containing news articles labeled as fake and true respectively. I explored four different machine learning algorithms: Logistic Regression, XGBoost, Decision Tree, and Random Forest Classifier, and evaluated their performance in detecting fake news.

## Files
- **fake.csv**: Dataset containing fake news articles.
- **true.csv**: Dataset containing true news articles.
- **Fake_News_Detection.ipynb**: Jupyter Notebook containing the code for data exploration, preprocessing, model training, and testing.
- **README.md**: This file.

## Approach
1. **Data Exploration**: I analyzed the structure and content of the datasets to understand the features and labels.
2. **Data Preprocessing**: I performed text preprocessing techniques such as tokenization, stop word removal, and lemmatization.
3. **Model Training**: I trained four machine learning models: Logistic Regression, XGBoost, Decision Tree, and Random Forest Classifier.
4. **Model Evaluation**: I evaluated the performance of each model using accuracy metrics.
5. **Testing Function**: I created a testing function that allows users to input news articles and get predictions on whether they are fake or true for each of the four algorithms.

## Results
- **Logistic Regression Accuracy**: 98.6%
- **XGBoost Accuracy**: 99.5%
- **Decision Tree Accuracy**: 99.6%
- **Random Forest Classifier Accuracy**: 99.1%

## Usage
1. Clone the repository: git clone [https://github.com/PeterKayode/fake-news-detection.git](https://github.com/PeterKayode/fake-news-detection.git)
2. Install the required libraries: `pip install -r requirements.txt`.
3. Open and run the Jupyter Notebook `Fake_News_Detection.ipynb`.
4. Follow the instructions in the notebook to explore the data, train the models, and use the testing function.

## Conclusion
My experiments show that the Decision Tree Classifier achieved the highest accuracy in detecting fake news among the four algorithms tested. However, the performance may vary depending on the dataset and the characteristics of the news articles. This project provides a starting point for further research and development in fake news detection.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


