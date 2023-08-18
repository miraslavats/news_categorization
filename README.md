# news_categorization
In this [project](https://github.com/miraslavats/news_categorization/blob/cb7c48d15d06444cd52286d8828a67c32e8948a8/News_categorization_project.ipynb) I am using Naive Bayes, RNN (LSTM, GRU, Bidirectional), CNN, Transfer Learning models to predict news category based on its short description (av. 11 words);

**GOAL**: Predict news category (out of 41 categories) based on news' short descriptions using machine and deep learning.
Concepts/Techniques practiced: NLP, RNN(Recurrent Neural Network) - LSTM, GRU, Bodirectional, CNN(Convolutional Neural Network), Naive Bayes, Transfer Learning, Wordclouds, EDA

**Conclusion**: After conducting EDA on the data set, I built several models to compare the results and choose the best performing one. The best performing model on unseen data was model_5 (transfer learning) with an accuracy score of 45.95%.

**Future Improvements**: Explore other ways to encode text data and their impact on a model's performance. Making the last model more complex since it has the most potential.

**Full Notebook**: [here](https://github.com/miraslavats/news_categorization/blob/cb7c48d15d06444cd52286d8828a67c32e8948a8/News_categorization_project.ipynb)

## Project Overview
1. Data Cleaning, Visualization, EDA:

   Publisher & Author frequency:
   <img width="904" alt="Screenshot 2023-08-18 at 9 18 25 AM" src="https://github.com/miraslavats/news_categorization/assets/112869592/f508d2da-74d6-44ee-9b82-4f937f504462">

   Wordcloud for all 41 categories:
   <img width="895" alt="Screenshot 2023-08-18 at 9 19 08 AM" src="https://github.com/miraslavats/news_categorization/assets/112869592/56affa66-1ebe-4fd9-a95a-d20a55d79147">
    
   Category-specific wordclouds:
   <img width="895" alt="Screenshot 2023-08-18 at 9 19 57 AM" src="https://github.com/miraslavats/news_categorization/assets/112869592/62bd929b-15fc-4b93-8c1d-a93aecb5f57b">

2. Textual Data Preprocessing;
3. Model Building:
   a. Naive Bayes:
   accuracy score on unseen data: 42.84%
4. Deep Learning:
   a. Text Vectorization & Embedding;
   b. Model_1: LSTM
     accuracy: ~39%
   c. Model_2: Adding Bidirectionality
     accuracy: 37.29%
   d. Model_3: GRU
     accuracy: 36.76%
   e. Model_4: Model_1 but less complex
     accuracy: ~35%
   f. Model_comb: Combination of all teh above layers
     accuracy: 38.9%
   g. Model_5: Transfer Learning
     accuracy: 45.92%

While this is not the best performance, the model is not purely guessing (we have 41 category). In the future, I am planning to go back to the very last model and improve it further.

   
