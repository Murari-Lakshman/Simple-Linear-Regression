# Simple-Linear-Regression
A Simple linear regression model to predict the salary using the experience of an individual.
This is model that is created only using numpy and matplotlib (with the exception of sklearn to determine how accurate our model is using r2 score). First we use a very simple dataset downloaded from Kaggle, The link to the dataset is right here (https://www.kaggle.com/datasets/abhishek14398/salary-dataset-simple-linear-regression). The data has ID, Years of experience and Their respective salary. Dataset has 30 examples. Our model is an python notebook called Sal_dat_lin_reg. This holds holds all the code necessary to implement the model.
A visualized description of how the data looks like:

![output2](https://github.com/user-attachments/assets/3f268688-0c61-425c-ad7e-15f8dc368368)

For this task I used Linear regression. Since the data values have massive differences, I also decided to scale the features using general scaling. This made the model faster and way easier to compute when around 10000 epochs are given.
For the cost function, we are using mean squared error cost function.
A general gradient descent(non-regularized) is used. 
To actually train the model, I gave the initial parameters to be w=0, b=0. The learning rate alpha as 0.01 (I experimented with several values of alpha from lesser to much bigger values but 0.01 was the sweet spot)
I trained the model for 10500 epochs (I experimented with many other epochs but after 10500 epochs convergence takes place leaving us with an accurate model).

A visualized representation of our model:

![output](https://github.com/user-attachments/assets/ccab434d-27cf-4d10-bb33-485629d50a59)

We used r2 score to guage the model's accuracy and found it to be 0.9968296864751057

Thank you for reading through!
