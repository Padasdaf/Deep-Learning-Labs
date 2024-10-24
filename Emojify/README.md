# Emojify
I built two models to create an "Emojifier" that suggests emojis based on input sentences. The first model (Emojifier-V1) used pre-trained GloVe embeddings, representing sentences as the average of their word vectors. The second model (Emojifier-V2) was a more advanced LSTM-based model that captured sequential information. Key steps included creating an embedding layer, converting sentences to word indices, and building a Keras LSTM model to classify sentences and predict emojis. This showed how word embeddings and LSTMs improve natural language processing tasks.