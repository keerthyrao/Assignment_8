700747373--Assignment-8-Keerthy Pabbathineni
Here is the video link: 

In class programming:

Add one more hidden layer to autoencoder
Do the prediction on the test data and then visualize one of the reconstructed version of that test data. Also, visualize the same test data before reconstruction using Matplotlib
Repeat the question 2 on the denoisening autoencoder
plot loss and accuracy using the history object dd one more hidden layer to autoencoder
A) This code first runs the provided code, following which we add some hidden layers in encode (the encoded representation of the input), along with decode (the lossy reconstruction of the input). This model plots an input to its reconstruction as well as the encoder for its encoded representation, and it is then compiled and loaded with the MNIST dataset, after which the data is normalized and flattened, and the autoencoder is trained.

Here is the screenshot regarding this explanation image

Do the prediction on the test data and then visualize one of the reconstructed version of that test data. Also, visualize the same test data before reconstruction using Matplotlib
Using the Matplotlib library, we will obtain the test set's reconstructed pictures for this. Using the image to be plotted's index, select a random image from the test set, and then use the imshow() function to plot both the original and the rebuilt picture.

Here is the screenshot regarding this explanation image

Repeat the question 2 on the denoisening autoencoder First, we ran the provided code, then we added a few lines to display the original noisy and reconstructed images by obtaining the reconstructed images for the test set, and finally by selecting a random image from the test set.
Here is the screenshot regarding this explanation image

plot loss and accuracy using the history object. Here, after importing Matplotlib, we are using the autoencoder to teach the autoencoder.We are showing the graphs of both loss and accuracy by using the fit() function, plotting the loss and accuracy, and declaring the title, xlabel, and ylabel functions in the plot() function.
Here is the screenshot regarding this explanation image image image
