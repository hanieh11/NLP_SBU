# NLP_SBU
Implemenetation of NLP mini tasks for NLP course in Shahid Beheshti university

1. **Persian sentiment analysis:** In mini-project I have used open-source SentiPers corpus to train 6 different models defined bellow
* RNN1: Glove-RNN(50)-maxpool-dp(0.2)-Dense(50)-dp(0.1)-Dense(50)-dp(0.1)-dense
* RNN2: Glove-RNN(50)-RNN(20)-maxpool-dp(0.1)-Dense(50)-dp(0.1)-dense
* LSTM1: Glove-60-maxpool-dp-Dense(50)-dp-dense
* LSTM2: Glove-LSTM(60)-dp(0.3)-LSTM(32)-maxpool-dp(0.4)-Dense(50)-dp-dense
* LSTM3 = cnn(64,7)-dp-cnn(32,7)-dp-GRU(60)-maxpool- dense
* GRU1 glove-gru(50)-maxpool-dp(0.2)-dense(50)-dp(0.1)-dense(50)-dp(0.1)-dense
* GRU2 glove-gru(50)-gru(32)-maxpool-dense(50)-dp(0.1)-dense

2. **Persian embedding:**  I have used FastText and Word2Vec from Gensim library to create embedding modules and for the Persian text proccessing part, both Hazm and Spacy have been used. Using this script you can create the word and text embeddings on Persian Corpus and then visualize it. 
