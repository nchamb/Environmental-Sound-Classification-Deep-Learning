# Environmental Sound Classification Using Data Learning
This project focuses on environmental sound classification using deep learning. The dataset contains audio recordings from 10 different environmental classes, and the task is to train models that can automatically recognize the type of environment or event from a short audio clip.

# Dataset Information
Dataset: URBANSOUND8K  
Classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, engine_idling, gun_shot, jackhammer, siren, street_music  
Features: Mel-spectrograms, MFCCs, log-Mel energy  
Labels: Single class per clip

# Deep Learning Model Architectures
Selected Model Architectures:
1. RNN (LSTM) + MFCC
2. Custom CNN + LogMel
3. Coordinate Attention Residual Transformer Neural Network + MFCC
