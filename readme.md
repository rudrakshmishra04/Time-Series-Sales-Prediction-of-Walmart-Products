Predicting Sales of Walmart Products
In the retail industry, forecasting sales accurately is important as this will help improve the revenue by avoiding can avoid wastages and shortages of products
The main objective is to estimate or predict the unit sales of Walmart retail goods at stores in various locations for the next 28-days, and 180 days.
30,490 forecasts must be made for each day.


This is a quick guide on installation of the libraries required to run the code. 
The project consists of two files-
-Rudraksh Mishra-Ambika Chundru-CNN-LSTM-CODE.ipynb
-Rudraksh Mishra-Ambika Chundra-DA-RNN-CODE.ipynb

CNN-LSTM file:
1) To run the CNN-LSTM model we need to install and import these libraries:
- itertools
- graphviz
- pydot
- pydotplus
- seaborn
- numpy
- tensorflow (version 2.6.0)
- keras (version 2.6)
- matplotlib
-scikit-learn

2) Running the code:
After the installation of the required libraries. The code can be run with the provided sales files in the right format(sales_train_evaluation,calendar,sell_prices)
Then with the change of input path you can run the code.
The code will run successfully and save the model weights named as "version3.h5". 
The output destination of the weights will be the same as the root directory where the code is running. 

DA-RNN file:
1) To run this file first we would need to create a seperate new environment to run on. This step is recommended as the DA-RNN libraries are still in developing mode and they end up changing the tensorflow versions.
- da-rnn[keras]
- graphviz
- pydot
- pydotplus
- seaborn
- numpy
- tensorflow (version 2.4.0)
- keras (version 2.4)
- matplotlib
-scikit-learn

2) Running the code:
After the installation of the required libraries. The code can be run with the provided sales files in the right format(sales_train_evaluation,calendar,sell_prices)
Then with the change of input path you can run the code.
The code will run successfully and save the model weights named as "DANGER.h5". 
The output destination of the weights will be the same as the root directory where the code is running. 

Contributors: Rudraksh Mishra and Ambika Chundru
