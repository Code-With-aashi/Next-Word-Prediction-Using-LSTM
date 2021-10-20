# Next-Word-Prediction-Using-LSTM

## LSTM Algorithm
Long Short Term Memory Network is an advanced RNN, a sequential network, that allows information to persist. It is capable of handling the vanishing gradient problem faced by RNN. A recurrent neural network is also known as RNN is used for persistent memory.
At a high-level LSTM works very much like an RNN cell. Here is the internal functioning of the LSTM network.The LSTM  consists of three parts:-

The first part chooses whether the information coming from the previous timestamp is to be remembered or is irrelevant and can be forgotten. In the second part, the cell tries to learn new information from the input to this cell. At last, in the third part, the cell passes the updated information from the current timestamp to the next timestamp.
These three parts of an LSTM cell are known as gates. The first part is called Forget gate, the second part is known as the Input gate and the last one is the Output gate.
### Steps used in the project:
1. Loading the data set.
2. Tokenization
3. Model Building
4. Executing the model.
