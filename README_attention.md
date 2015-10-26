# LSTM-and-Varieties
The use of LSTM model by Theano in NLP  ,and sorts of similar varieties 

The attention method could be easily described as this:

1. Initialize a Vector as R(d) , d is the number of the dimentions of Word-vector .
2. Use the Vector,which could be named as Intention Vector,to calculate the dot product of the Vector and each Word in your training set(batch).
3. Use the numpy(which is just a scalar) as the weight of the Hidden Status H(t),to get a final result of the sentence rather than the method of Mean-pooling.

