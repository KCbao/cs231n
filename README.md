# cs231n

## Assignment 1
- [x] Q1-Q5

### FeedBacks from A1
1. Q1: predict_labels, pass does not predict so 11% accuracy not 27%. Incline question 2: Option 1,2,3 leave the performance unchanged while option 4 does, becuase per pixel division changes the L1 sum. Cross-validation fails because of problem in predict_labels.

- fix predict_labels function, now cross-validation succeeds with test accuracy above 28\%.  update inline question 2 with more explanations. 

## Assignment 2
- [x] Fully Connected Neural Network 
- [x] Batch Normalization 
- [x] Dropout
- [x] Convolutional Networks
- [x] PyTorch / TensorFlow on CIFAR-10

### Feedbacks From A2

1. Q1: Q1&2 partially answered, did not get 50\% on final question

- Fix last question, fine-tuned the hyperparameter weight-scaling. The best model occurs at weight-scaling equals 0.05614074602717004, the corresponding validation accuracy is 55.4%, and the test accuracy is 53.4%. 

2. Q2: batch norm not implemented correctly

3. Q3: increase p when layers are smallers, 40\% of 2 neurons layer can result in both neurons dropped, Dropout does not reduce capacity of network, just slows down trainings. important to not dropout too many neurons. 

- Solved. Re-do Inline Q3, and explain why adding dropout will slow down training. 

4. Q5: both TF and PT did not get 70\%. 

- The open-ended challenge in both TF and PT notebooks now get more than 70\% accuracy. TF's implementation is included in a separated notebook named "TF-open-endedChallenge.ipynb". 


## Assignment 3
- [x] Q1
- [x] Q2

## Final Project
- [x] model 1, model 2, report
- To run notebooks, you need to SICK dataset, and GloVe dataset ([glove.6B.zip](https://nlp.stanford.edu/projects/glove/)), place them under /data folder. 