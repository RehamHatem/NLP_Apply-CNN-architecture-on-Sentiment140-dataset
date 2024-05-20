The code is designed for text classification on Sentiment140 dataset
using a Convolutional Neural Network (CNN) model. It's structured to 
handle preprocessing of text data came from the data set in column 6, 
data loading from a CSV file, splitting the data into training and testing 
sets (80%,20%)with length(1279999, 320000), encoding labels which is
the polarity in the data set (0,4,)to do classification on it , tokenizing the 
words, and padding text sequences, defining a CNN model with various 
filter sizes(3,5,7), training the model on the training set, and evaluating 
its performance.
