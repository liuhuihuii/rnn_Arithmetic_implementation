# rnn_Arithmetic_implementation
A implementation of sequence to sequence learning for performing addition,substraction,multiply,divide with LSTM neural network by Keras

this experiment mainly achieve the arithmetic by learning the right dataset,except the mult.py cannot perform well,only about 77% accuracy in the 
validation set,others can up to 99% accuracy.
this scripts can only calculate the 3-digit two num,you can change the generate_data() the function to achieve more digits arithmetic.
I just wanto to using LSTM to handle the sequence to sequence data problem,with using Keras,fast deep neural network to achieve your idea.

the rnn_addition.py comes from the Keras team,I just use it,others is modified by me to validate the expand other case whether has the same 
good performance,
you can refer to https://github.com/keras-team/keras/blob/master/examples/addition_rnn.py,the origin code url.
