# New-York-Stock-Exchange--Regression
After merging the datasets: prices-split-adjusted, fundamentals, securities, ive cleaned it by removing rows with missing values and duplicating rows, after that ive worked on numerical columns to handle regression task, the target variable chosen is the column close, ive add some computations about correlation between this column and other columns, ive chose the variables have the highest corr as input variables and i applied the regression based on them
the model:
the regression task implemented that i ve chosen is predicting stock closing price
The dataset is split into training and testing sets and the input features are standardized
The neural network consists of three fully connected layers with ReLU activation functions and the model is trained using MSE loss, Adam optimizer and gradient clipping. Training occurs over 100 epochs
results:
Over the 100 training epochs, the model learned to predict stock closing prices based on input features, starting with a high error that gradually decreased to a much lower value
