# AI-Snake-Game-WiDS
I used the cross entropy loss and adam optimiser, and have chosen the values of hyperparameters as: 
hidden layer size = 1000
number of epochs = 16
batch size = 200
learning rate = 0.001

These values are obtained from the following data I generated to obtain the maximum accuracy:
Variation of hidden_size
num_epochs = 2
Learning_rate = 0.001
batch_size = 100

Hidden_size = 10: 91.46%
Hidden_size = 50: 93.95%
Hidden_size = 100: 95.21%
Hidden_size = 200: 96.10%
Hidden_size = 500: 97.08%
Hidden_size = 2000: 97.74%
Hidden_size = 3000: 97.63%
Hidden_size = 4000: 97.56%

Variation of epochs
hidden_size = 500
Batch_size =300
Learning_rate ‎ = 0.001

num_epochs =1: 94.24%
num_epochs =2: 95.87%
num_epochs =4: 97.23%
num_epochs =8: 97.61%
num_epochs =12: 98.10%
num_epochs =16: 98.15%
num_epochs =20: 98.26%
num_epochs =24: 98.10%
num_epochs =28: 98.23%
num_epochs = 32: 98.19%

Variation of Learning rate
num_epochs=12
Batch_size=200
hidden_size=500

Learning_rate =0.0001: 95.86%, 26.47s
Learning_rate =0.0005: 97.96%, 24.24s
Learning_rate =0.001: 98.03%, 24.12s
Learning_rate =0.005: 97.97%, 24.50s
Learning_rate =0.01: 97.63%, 24.60s
Learning_rate =0.05: 94.1%, 25.29s
Learning_rate =0.10: 86.38%, 25.49s

Variation of activation function
num_epochs ‎ = 12
Batch_size=200
hidden_size=500
Learning_rate=0.001

ReLU: 98.08%, 98.03%
LeakyReLU: 97.95%, 97.90%
Sigmoid: 97.74% 97.47%
TanH: 97.82%, 97.91%
