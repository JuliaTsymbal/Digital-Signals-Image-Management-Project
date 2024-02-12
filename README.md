# Digital-Signal-and-Image-Management-project
In the following project dedicated to Digital Signal and Image Management, different approaches have been studied for 3 problems.

# Processing of one-dimensional signals:
It’s a task of language classification. We took 3 languages: Italian, English, Ukrainian. Using MFCC features we trained simple NN with 2 GRU layers and 1 Dense to classify audio records in 3 different languages. Trained NN can be uploaded from a file RNN_2layers_F20_3lang_5000.keras and can be used for audio classification. The model was tested on new unseen data from the original dataset.  
Data was taken from Kaggle: [link](https://www.kaggle.com/datasets/shrivatssudhir/language-identifier?select=basque)

# Processing of two-dimensional signals:
It’s a task of video classification. We took 5 classes: Bench pass, Shaving beard, Punch, Playing Guitar and Drumming. Using pre-trained MobileNetV2, features were extracted. We trained the NN model with 4 GRU layers and 3 Dense layers to classify video frames. Classification performance was tested on a few videos from the Internet. 
Data was taken from Kaggle: [link](https://www.kaggle.com/datasets/matthewjansen/ucf101-action-recognition)

# Retrieval task:
The goal is to return faces more similar to a face given as input, extrapolating them from a large dataset of celebrity photos.
To achieve the goal, a pre-trained Haar Cascade classifier for detection was used, and then as a feature extractor was pre-trined VGG16 model. For the search was used K-Dimensional Tree, BallTree.
Data was taken from Kaggle: [link](https://www.kaggle.com/datasets/stoicstatic/face-recognition-dataset)

# Software
We used Python for this project.

# Team
Yuliia Tsymbal y.tsymbal@campus.unimib.it

Sara Campolattano s.campolattano@campus.unimib.it

Induni Sandapiumi Nawarathna Pitiyage i.pitiyage@campus.unimib.it
