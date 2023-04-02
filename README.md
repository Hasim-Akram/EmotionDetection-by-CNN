# EmotionDetection-by-CNN

# Emotion_detection_with_CNN

![emotion_detection]

### https://github.com/Hasim-Akram/EmotionDetection-by-CNN

### Packages need to be installed

- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow

### download FER2013 dataset

- from below link and put in data folder under your project directory
- https://www.kaggle.com/msambare/fer2013

### Train Emotion detector

- with all face expression images in the FER2013 Dataset
- command --> python TranEmotion.py

It will take several hours depends on your processor. (On i5 processor with 8 GB RAM it took me around 4.5 hours)
after Training , I will find the trained model structure and weights are stored in my project directory.
emotion_model.json
emotion_model.h5

copy these two files create model folder in my project directory and paste it.

### run your emotion detection test file

python TestEmotion.py
