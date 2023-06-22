# Emotion_based_music_recommendation_system
A web app based on Python to recommend a list of 30 songs on the basis of the user's emotions captured via webcam.

Download the fer2013.csv dataset to generate the images from the dataset_preparation.ipynb file from:
https://www.kaggle.com/datasets/deadskull7/fer2013

# Abstract
A python-based web app using Streamlit to recommend songs based on the user's emotions scanned via a webcam. I used the fer2013 dataset to generate a number of sample images of different emotions to train our model. Then I used CNN and Haar Cascade algorithms to create a model which classifies the user's emotions. This model is then used to recommend musics from the muse_v3 dataset according to the emotions classified. The model has an approx Training accuracy of 87% and a Testing accuracy of 66%.
