We basically look into Deep Learning approach where we remove fake reviews in perspect of a company for better functionality You can get an interesting aspect where many companies who manufacture products actually do alter their supply and market costs according to the user reviews. For this in a competitive business world, we cannot solely consider reviews blinddly to decide the above factors. So,we need to find the genuine reviews of those against any product or a place or anything and based upon a public point of view we are gonna do character by character analysis and perform the elimination of fake reviews to an extent.

We used the concepts of Deep Learning using python and other libraries as of :Keras and Tensorflow which were used as standard libraries in python for machine learning aspects and predictive analysis.

Recurrent neural networks are used in this manner to train the machine or say a program to predict the genuinity of a review where the character that comes next depends on the memory that we maintain till then and the chance that this particular character is to be present in that review solely depends on this memory that the machine maintains till then.

We start with a rich dataset of reviews regarding say a computeror a sort of device where we group the characters and count the frequency of each character and by the next time to predict some character to take it or not is decided by the LSTM functionality added to RNN.But if we see rather than convolutional neural networks and feedforward approach this one being Recurrent improves the weight of each character after each cycle and based upon that weights the considerations are taken. So we encounter fake reviews where we may eliminate them to an extent.In the scenario of updating weight set at each iteration, we use Adams Optimizer which is a key role in today's deep learning methodoligies.It learns at a faster pace rather than traditional Gradient Descent approach of updating the weights and based upon the learning rate the scale of using Adams Optimizer made this project a fruitful one ..... So at the end of each iteration you wil be getting the repeating set of words and lines in the step by step fashion in a generation of 3 generations.Based upon the learning rate you give to the optimizer your results serve some lossed and the suggested learning rate is 0.02 for Adam Optimizer.
