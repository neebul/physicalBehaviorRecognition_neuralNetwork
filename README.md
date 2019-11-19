# activityRecognition_neuralNetwork
Creation of a neural network to recognize physical behaviors with accelerometer data. The original code was made to differentiate lying, sitting, standing, walking and running. 
In this project, features were generated using the raw data of a dual-accelerometer system. 

Data is organized as follows: 
- a column identifying the subjects of the experimentation (id)
- a column for the activity realized
- columns for the features 

You will obtain as results: 
- in 'evaluation', the accuracy of the predictions of the model for each subject
- in 'errors_nn', the detail of each error made by the model: index of the error, activity category wrongly predicted, true activity category, and the probabilities calculated for each category
