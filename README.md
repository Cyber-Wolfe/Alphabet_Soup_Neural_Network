# Alphabet Soup Neural Network

## Purpose

The purpose of this analysis is to understand whether a neural network can predict, from a provided dataset, if applicants will be successful if funded by Alphabet Soup.

## Results

The beginning DataFrame after file export had looked like the image below, and needed some immediate cleaning and direction for our model to begin:

![Main_Dataframe.PNG](https://github.com/Cyber-Wolfe/Neural_Network_Charity_Analysis/blob/main/Resources/Captures/Main_Dataframe.PNG)

*Pre-Processing*

* The target of this data set was the "IS-SUCCESSFUL" column of the data set.

* The features would be the rest of the dataset.

* This is barring EIN, Name, and ASK_AMT becuase they will be removed from the dataset.

![Target_features.PNG](https://github.com/Cyber-Wolfe/Neural_Network_Charity_Analysis/blob/main/Resources/Captures/Target_features.PNG)

![Removed_data.PNG](https://github.com/Cyber-Wolfe/Neural_Network_Charity_Analysis/blob/main/Resources/Captures/Removed_data.PNG)

The final DataFrame now looks like the image below after cleaning:

![Filtered_Dataframe.PNG](https://github.com/Cyber-Wolfe/Neural_Network_Charity_Analysis/blob/main/Resources/Captures/Filtered_Dataframe.PNG)

*Compiling, Training, and Evaluating the Model*

![Layers_neurons.PNG](https://github.com/Cyber-Wolfe/Neural_Network_Charity_Analysis/blob/main/Resources/Captures/Layers_neurons.PNG)

* From the image above we can see there were 35 neurons, used across three layers and an activation function of relu, sigmoid, relu and then sigmoid for the 1st,2nd,3rd and output layer respectively.

* I was only about to get as high as .7258 accuracy for the model even when the tested accuracy had reached .7404 during epoch training.

* The steps I had taken, which aren't all shown, would be changing the epoch amount, adding layers, or adding neurons.

* I had even taken a more pre-process approach of dropping columns like INCOME_AMT and ASK_AMT.

## Summary

The overall results were a 73% accruacy after fitting the model with different layers, neurons, acivation functions, epochs and data. The machine learning model probably would have done better if I had a more concrete grasp on the implementation of said models.  Maybe a random-forest model would be better to use or a regression for classification.  Using either of those could prove far better because they are made for segementing groups more effectively.


