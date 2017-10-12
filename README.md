# Edible-or-Poisonous
Determining which mushrooms are edible or poisonous with an artifical neural network. 

Preprocessing:
For the mushroom dataset there were a few steps of pre-processing I had to do before I was able to work with the data. I removed the veil-type variable since it was of just one class and might end up skewing my results. I created dummy variables so each feature could be tested more easily.
 
NEURAL NETWORK

For my artificial neural network I explored a few options shown below. I followed through with the same preprocessing steps as the SVM, except I converted my features into a factor F that could be passed to my neural network.

200 Iterations




100 Iterations w/ 2 layers


100 Iterations 3 hidden layers


While working through both the SVM and nnet I had a few concerns about the accuracy rate. It’s highly important to consider the type of data one is working with and which measure of error makes the more sense. With our mushroom dataset it makes more sense to be worried about reducing the number of false positives than false negatives. If our classifier finds a mushroom to be edible when it’s poisonous, there’s more damage there than if it encounters a false negative. 


