# Emotion_based_music_recommendation_system
A web app based on python to recommend a list of 30 songs on the basis of the user's emotions captured via webcam.

Download the fer2013.csv dataset to generate the images from dataset_preparation.ipynb file from https://www.kaggle.com/datasets/deadskull7/fer2013

#Abstract
A python based web app using streamlit to recommend songs based on the user's emotion scanned via a webcam. I used the fer2013 dataset to generate a number of sample images of different emotions to train our model. Then I used CNN and Haar Cascade algorithms to generate a model which classifies the user's emotions. This model is then used to recommend musics from muse_v3 dataset as per the emotions classified. The model has an approx Training accuracy of 87% and Testing accuracy of 66%.
