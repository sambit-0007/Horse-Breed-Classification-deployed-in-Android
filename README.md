### Horse-Breed-Classification-deployed-in-Android
End to End implementation of Horse Breed Classifier in Android Studio

The objective is to find a Deep Learning Classifier algorithm (Convolutional Neural Network) to detect breed of the horse presented in the image.
I have built a CNN model to train which then classifies the images in 7 categories.

Once the model is good to predict the horse breed, I have created a tflite format out of it and implemented it in the Android Studio. 

### Dataset
  This dataset contains a data folder which contains 7 subdirectories namely

### Image Preprocessing
All the images are not of the same size, and neural networks often expect images that are standardized; a fixed size. Therefore, the following preprocessing steps are performed:
    Normalize
    Resize
    Reshape


### Model Building and Training :
  Here a basic model is built using CNN and Keras library.
  Model is first trained on all kind of Horse breeds. 
  Then model is tested on sample test data. Whichever model is giving the good accuracy that model is saved for further use.
  
### Model Prediction
  The following steps are performed here:

  Loading the previously saved model(best model) from training phase.
  passed a image through the model to predict the breed of the horse.

##### Reload the page to play the below gif.
  <img src="horse breed classifier.gif" title='Horse Breed Classifier' width="250" align="center">

