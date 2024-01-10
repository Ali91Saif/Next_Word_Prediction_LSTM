# Next_Word_Prediction_LSTM
For this project, i have developed RNN Model for Next Word prediction in movie's title. I have implemented LSTM gating with RNN architecture to predict the next word. 

DataFrame Consists of 4803 movies data Instances (ROWS), and information is distributed accross 20 Attributes. 

After tokenization and sequencing, Input data and Output data is being seperated and stored in variable X and y respectively.

Model Architecture Contains:
1 Embedding Layer
3 LSTM Layers
1 Fully connected Layer using Activation Function 'ReLU'.
1 Output Layer using Activation function 'Softmax'

Hyperparameters:
Loss_Function used is 'Categorical Cross_Entropy'.
Optimizer used is 'Adam'. 
Learning_rate is kept at 4e-3 
Number_of_Epochs is set to 150

Model_Performance:

Accuracy Matrix is obtained to judge the performance of the model.

** Even after 150 epochs, model has failed to capture the information and performed very poor, here i need to fine tune the hyperparameters and need to run for even more number of epochs for better performance.
