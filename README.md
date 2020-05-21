# Reverse Image Search using deep learning models.


Have you ever wondered how google image search works ? or How amazon is able to retrive products similar to the image that we upload in the app/site.We will use one simple method to acomplish the task.

We will pick a pre-trained deep learnig model, remove the top layers and extract the convolutional features for the images in our dataset. Then we will use these feature vectors to find similar images by using sklearn's nearest neighbors algorithm
