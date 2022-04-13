# RecognitionModel
Graduation Thesis of Data Analytics of IOT (2019)

Face Recognition With Cloud Computing

This project is a facial recognition prediction project with an android application. The project consists of 3 parts: Android application, Recognition model and Flask API.
Briefly, the project works like this: We send a face photo taken with the Android application to the Flask API, where the Recognition Model is installed, via the ngrok tunnel. Then the Flask API sends a response to the Android application. And we see this response on the screen.

I am proud to say that this project is done by me Onur Saldamlı and my team mate Ezgi Eftekin and is our graduation thesis.

About Code:

Since this project is done through Google Colab, first of all, the Google Drive account must be mounted.
Before creating a model, we must process our train data  in order to create the model as quickly and as accurately as possible. We reconstruct each of the train data with the ImageDataGenerator() function. We reconstruct each of the train data with the ImageDataGenerator() function.

We create the model with Sequental() and then create the layers of the model. We designed such a model by seeing that 5 layers gave better results through trial and error.


