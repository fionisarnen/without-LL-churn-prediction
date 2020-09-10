# without-LL-churn-prediction
This implementation will compare the significant performance of churn prediction before using Lifelong Learning concept.

Scenario : xA,yA as the previous task (Task 1) and xB,yB as the new task (Task 2). What we want to focus:

the normal or 'traditional' sequential training vs dynamic sequential training
proof that ewc overcome fogetting while the traditional suffer from forgetting (also overfitting)
here the model use Keras as the training system by training on new task while validating on previous task. The sign of quality performance shown by trainset (which on new task) and testset (on prev task)

The normal sequential training with Neural Network

