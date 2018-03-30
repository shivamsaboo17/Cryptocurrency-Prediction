# Cryptocurrency-Prediction
LSTM deep learning model for cryptocurrency price prediction!</br></br>
![](https://themerkle.com/wp-content/uploads/shutterstock_550971307-1.jpg)</br>

## How this works?</br>
Predicting crypto prices, stock prices, weather etc are all examlpes of time series forecasting. The idea is the future prediction depends on past information. RNN's and LSTM's have proved to be state of the art for these kinds of predictions. Due to this property i.e predicting on basis of previous context have made them favourite candidates for tasks like machine translation and language modelling. In fact Google Translate works on a much advanced and complex model of LSTM!
## What is LSTM?</br>
LSTM's are sophisticated RNN units.</br>
#### What is RNN!?</br>
Humans don’t start their thinking from scratch every second. As you read this essay, you understand each word based on your understanding of previous words. You don’t throw everything away and start thinking from scratch again. Your thoughts have persistence.

Traditional neural networks can’t do this, and it seems like a major shortcoming. For example, imagine you want to classify what kind of event is happening at every point in a movie. It’s unclear how a traditional neural network could use its reasoning about previous events in the film to inform later ones.

Recurrent neural networks address this issue. They are networks with loops in them, allowing information to persist.</br></br>
![Recurrent Neural Network](http://colah.github.io/posts/2015-08-Understanding-LSTMs/img/RNN-unrolled.png)</br>
While RNN may seem to be a good candidate for this task...unfortuanately it's not. RNN's, while they are good at storing short term dependencies, they are disaster when you need to keep track of longer dependencies due to vanishing gradient problem.
#### LSTM to the rescue!</br>
LSTM's are capable of stroring longer dependencies as it can decide on which information it should retain and which information it can throw away. A LSTM cell looks like this:</br>
![LSTM](http://colah.github.io/posts/2015-08-Understanding-LSTMs/img/LSTM3-var-GRU.png)</br>
These cells are really powerful in capturing context from long sequences hence is the state of the art.
#### So now we have a very basic model to predict not just crypto prices but any time sequence such as weather, stock prices, language modelling etc!
