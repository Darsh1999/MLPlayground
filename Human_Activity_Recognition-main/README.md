# Human Action Recognition

## Abstract

The realm of video analysis has witnessed remarkable progress, shifting its focus from understanding the current state to forecasting future states. These advancements have been made feasible through the development of Computer Vision and Machine Learning technologies. In the domain of action recognition based on visual cues, a wide range of human activities can be inferred by analyzing their complete movements. This capability also extends to predicting the forthcoming actions performed by individuals. Given its direct applicability to real-world challenges such as visual surveillance, autonomous driving, and entertainment, human action recognition has garnered significant attention in recent years. Extensive research has been conducted to develop robust action recognition systems, and the field continues to witness further advancements as its utility spans across numerous domains.


## Problem Statement

Can an automated system accurately identify the action being performed in a video? The process of action recognition relies on a series of fundamental steps. Firstly, the system takes in the input video or sequence of frames. Next, it extracts low-level features from these frames. Finally, it generates mid-level pose/gesture or action descriptions based on the extracted low-level features.


#Dataset
The UTF50 Human Action Dataset is a comprehensive collection of video data specifically designed for human action recognition tasks. It is a valuable resource in the field of computer vision and machine learning, providing researchers and practitioners with a diverse and realistic dataset for training and evaluating action recognition models.

This dataset consists of 50 different human actions captured from various perspectives and environments, offering a wide range of scenarios and movements. The actions cover a broad spectrum, including everyday activities, sports, gestures, and interactions. Each action is recorded in multiple video sequences, capturing different variations and perspectives to ensure robustness and generalization of the models.

## Methodology

We used “Google Colab” to run the programs. It provides us approx. 12 GB of RAM
and variable GPU depending on the traffic.


##### Steps include:
- Working with the dataset.
- Extracting features from the frames using CNN.
- Passing those features into a recurrent neural network to train the model and classifying.
- Saving the best model and then using it to classify the videos.


## Conclusion

Deep learning models have proven to be effective in addressing the human action recognition problem. However, when the temporal nature of videos is not taken into account, the accuracy of video classification tends to suffer.

In order to improve the accuracy of human action recognition, it is crucial to incorporate spatio-temporal understanding. By considering both spatial and temporal aspects, we can achieve better results in accurately recognizing human actions.

In our implementation, we utilized a new model that achieved a validation accuracy of approximately 81.5% on the UCF50 dataset, which is quite substantial. Additionally, the loss of the new model was significantly lower compared to the previous model, which only achieved a 25% accuracy.
