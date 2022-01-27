# toxicBERT

Steps for this step:
* Lowercasing all the words in the comments
* Use spaCy to tokenize the comments
* For each token in each comment, use toxicBERT to predict if current token is toxic
* If it is, record the index. Otherwise go to the next token
* Repeat above steps for each comment

Drawback for this method:
* Using this method, we cannot predict whether a token is toxic or not based on the context which will lower the accecury

Score for this method is *58%*