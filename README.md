# Edible-or-Poisonous
Why the fuck would you eat a wild mushroom to begin with? Just don't.

Preprocessing:
For the mushroom dataset there were a few steps of pre-processing I had to do before I was able to work with the data. I removed the veil-type variable since it was of just one class and might end up skewing my results. I created dummy variables so each feature could be tested more easily.
 
NEURAL NETWORK

For my artificial neural network I explored a few options shown below. I followed through with the same preprocessing steps as the SVM, except I converted my features into a factor F that could be passed to my neural network.

200 Iterations


![picture1](https://user-images.githubusercontent.com/6904744/31474869-b16aeb6e-aeba-11e7-9a57-5ac6066fd1c7.png)

100 Iterations w/ 2 layers

![picture2](https://user-images.githubusercontent.com/6904744/31474888-c38085ac-aeba-11e7-9721-1f4e3b2d11b4.png)

100 Iterations 3 hidden layers

![picture3](https://user-images.githubusercontent.com/6904744/31474897-d4765076-aeba-11e7-9094-9ecc6f55aedb.png)

While working through both the SVM and nnet I had a few concerns about the accuracy rate. It’s highly important to consider the type of data one is working with and which measure of error makes the more sense. With our mushroom dataset it makes more sense to be worried about reducing the number of false positives than false negatives. If our classifier finds a mushroom to be edible when it’s poisonous, there’s more damage there than if it encounters a false negative. 


