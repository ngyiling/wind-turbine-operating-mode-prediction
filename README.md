# Prediction of wind turbine operating mode
This aim of this project is to predict a wind turbine operating mode based on time series data from 2 sensors. Various models including Recurrent Neural Network (RNN) and Convolutional Neural Network (CNN) models have been used to identify the best performing model. The project has been guided by the [article on "CNN fault classification based on time series analysis for wind turbine machine" by Rahimilarki, Gao, Jin, and Zhang (2022).](https://www.sciencedirect.com/science/article/abs/pii/S0960148121017778) 

<br >

**Technology:** Pandas, Matplotlib, Scikit-learn, Tensorflow, Tensorflow.keras 

<br />

 **Results:** 
 - In addition to training different models including GRU, LTSM, 1D CNN and 2D CNN, the models convolutional layers, epochs, and learning rate have been optimised to obtain accuracies of above 80%. 
 - The best model identified was the 2D CNN with three convolutional layers due to its higher accuracy and lower training loss. 
 - The final model gave a test accuracy score of 0.91 and a loss of 0.23. 
