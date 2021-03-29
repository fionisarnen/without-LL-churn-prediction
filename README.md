# without-LL-churn-prediction
This implementation will compare the significant performance of churn prediction before using Lifelong Learning concept.

Scenario : xA,yA as the previous task (Task 1) and xB,yB as the new task (Task 2). What we want to focus:

The normal or 'traditional' sequential training vs dynamic sequential training. Proof that EWC overcome fogetting while the traditional suffer from forgetting (also overfitting). Here the model use Keras library to build baseline model as the training model. It works by training on new task while validating on previous task. Indication for quality performance shown by trainset (which on new task) and testset (on prev task)

This repository directly connected to my other repository:
https://github.com/fionisarnen/Lifelong-Learning-churn-prediction-torch

> You can find more about this project through my publications :https://ieeexplore.ieee.org/document/9212924

