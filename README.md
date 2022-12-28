# next-word-predictor

![Framework](https://user-images.githubusercontent.com/92006889/209802144-8f280ed1-86ca-4f2a-b978-21692dadceec.JPG)

Next Word Prediction is language modeling technique,undertaking of predicting what word comes straight away in the sonnet.My aim is to create this simple model to predict the 90 words or more as possible in minimum time.

Predictions are based on the context of other words in the message and first data provided.

Here,I fed with 2200 lines of Shakespeare's sonnet.When the model is trained with 10 initial words,It should be capable of  providing the output of next 90 words.

The main algorithm applied here is Long Short Term Memory (LSTM),LSTM model has built-in memory function, understands the past text and predict the words.

LSTM is majorly used because it uses gates to flow gradients back in time and reduce the vanishing gradient problem.This expect to create auto-complete features using LSTM.

Used for active learning, extracting highlights,writing fluency for students.

How it works:
1.Tokenization: Converts text to sequence
2.n-grams-generation: n-gram words from the given corpus
3.padding:which will pad any given sequences to the desired maximum length
4.Create model: LSTM Algorithm
5.Model in action: Trained for different amounts of epochs and seen how this affects the coherency of the generated text
