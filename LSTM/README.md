# BiLSTM

Steps for this step:
* Lowercasing all the words in the comments
* Find toxic words from the text using the span provided, and transform the text into a sequence where 1 represent toxic word and 0 means non-toxic word
* Vectorize the text using tf.keras.preprocessing.text.Tokenizer
* Build a BiLSTM model
* Train the model using training data and velidation data
* Predict the testing data

Drawback for this method:
* It's hard for this method to predict the span, since it's trained to predict whether a word is toxic or not.

Score for this method is *83.62%*