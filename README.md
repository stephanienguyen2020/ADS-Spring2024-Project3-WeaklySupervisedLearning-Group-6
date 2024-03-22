# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2024

+ Team 6
+ Team members
        + Rishabh Ganesh
	+ Tien Nguyen
        + Alex Chen
	+ Danielle Solomon
	+ Boyu Li

+ Project summary: In this project, we are building weakly supervised machine learning models that tackle the problem of noisy labels in the dataset. The goal for our project is to classify the CIFAR-10 dataset of 50,000 images as accurately as possible despite noisy labels using weakly supervised learning techniques like label correction. A logistic regression model was used as the baseline prediction model and resulted in a 24% accuracy. A Convolutional Neural Network model was created to attempt to improve the accuracy from the baseline and this model trained on the same data, produced an accuracy of about 32%. Though improvement came from the change in model, there was still a need for greater accuracy in prediction. The more complex Inception-v3 model was trained on clean data and resulted in the most accurate model with an accuracy of about 80%. 
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
