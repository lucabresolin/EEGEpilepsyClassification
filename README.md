# EEGEpilepsyClassification
Topic:
EEG epileptic spike detection is a crucial and challenging problem in both data science and neural science. 
The goal is to develop an algorithm to automatically detect whether an instance (such as EEG data series) captures an epileptic spike or not. 
Two common challenges are a). epileptic spike behaviors are minorities compared to normal behaviors; 
b). epileptic spike morphologies across different patients are quite different. In this project, you will tackle both challenges in the two tasks.

The main method used in EEG_CLASSIFIER use signal data without feature engineering except splitting it into its 5 channels. The machine learning models are then trained in each
channel and then their predicitons are merged with a final model. Our results are satisfying, 
especially in the context of the kaggle competition around it (we managed to reach #1 place before it ended).

Another way we tried to make it work was using DeepLearning from keras, it worked well too but not as well as planned and was roughly as precise as our classic try with mainly RandomForest classifiers.

