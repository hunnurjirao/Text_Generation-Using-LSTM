# Text_Generation-Using-BiDirectional LSTM
Text generation using BiDirectional LSTM

In text generation, we try to predict the next character or word of the sequence. The text data generally considered as sequence of data. For predicting data in sequence we used deep learning models like RNN or LSTM. LSTM are preferred over RNN in this because of RNN vanishing and exploding gradients problem. Since in text generation we have to memorize large amount of previous data. So for this purpose LSTM are preferred.

The phrases in text are nothing but sequence of words. So, LSTM can be used to predict the next word. The neural network take sequence of words as input and output will be a matrix of probability for each word from dictionary to be next of given sequence. The model will also learn how much similarity is between each words or characters and will calculate the probability of each. Using that we will predict or generate next word or character of sequence.

![](https://iq.opengenus.org/content/images/2019/12/1_XvUt5wDQA8D3C0wAuxAvbA.png)
