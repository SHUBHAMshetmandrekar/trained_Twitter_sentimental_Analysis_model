This project performs sentiment analysis on tweets, classifying them as positive or negative using a Logistic Regression model. The model is trained on the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140) and is saved as `trained_Twitter_sentimental_Analysis_model.sav` for future predictions.

**Files in this Repository**
- **Google Colab Notebook**: [Sentimental Analysis](https://colab.research.google.com/drive/1_6aWJLwNe_t3j1IMOrwgaPPsCVwTZZlq?usp=sharing)
- **Trained Model**: `trained_Twitter_sentimental_Analysis_model.sav`

**Project Steps**
1. **Data Preprocessing**: Clean and stem text to remove noise.
2. **Vectorization**: Convert text to numerical format with TF-IDF.
3. **Model Training**: Train a Logistic Regression model on the processed data.
4. **Model Evaluation**: Evaluate accuracy on training and test datasets.
5. **Future Predictions**: Load the saved model to predict sentiment on new data.

**Reference**
For a step-by-step guide on building this project, refer to the [YouTube video tutorial](https://youtu.be/4YGkfAd2iXM?si=D7j8q6oxWvTqJFgn).
