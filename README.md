# Supply-Chain-forecasting-deep-learning

Problem Statement:
1. Understanding sales trends to forecast future sales
2. Inventory Optimization: matching store inventory with actual needs to reduce storage space needed/rental cost
3. Replenishment Optimization: optimizing replenishment quantity per order to minimize the number of replenishments between warehouse and stores 
(Warehousing & Transportation Costs)
4. Finding out factors that affect sales to design and optimize the business model

Comparision between Machine Learning and Deep Learning models:

Machine Learning Models used:
1. Linear Regressor: Model  finds the best fit linear line between dependent and independent variables
2. XGBoost: Implementation of Gradient Boosted decision trees

Deep Learning Models used:
1. CNN: Feedforward neural network effective in forecasting time series problems
2. LSTM: It is a form of RNN which overcomes the shortcomings of RNN models
3. CNN+LSTM: Used to extract the features of the input time data and predict the same for the next day 
4. GRU: Designed to avoid vanishing gradient problem with fewer parameters.
5. Transformers: Adopts the mechanism of self-attention, differentially weighting the significance of each part of the input data. 

Conclusion:
ML model XGBoost and DL model CNN+LSTM prove to be more accurate in this project.

Advantages of XGBoost Model:
1. Produce reasonable forecasts with no hyperparameter tuning 
2. Demand for fewer data and fewer features
3. Explicitly adds a regularization term to the objective function to control the complexity of the model
4. Prevents overfitting, and improve the generalization ability 
5. Supports parallel selection of split points, thereby increasing the operating speed

Advantages of CNN+LSTM Model
1. Convolution Layer: The characteristics are derived from the data 
2. Grouping: Reduces the dimensionality of each feature map but retains the most important information 
3. Flatten: Converts the data into a 1D matrix to enter it in the next layer. 
We flatten the output of the Convolutional layers to create a single long feature vector.
4. Fully Connected: This helps connect each neuron in one layer with each neuron in another layer

 

