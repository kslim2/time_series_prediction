# Time Series Prediction 

Time series prediction problem are a difficult type of predictive modeling problem. Time series adds the complexity of a sequence dependence among the input variables.

# Long Short-Term Memory Network 

The Long Short Term Memory (LSTM) network is a recurrent neural network trained using backpropagation through time that overcomes the vanishing gradient problem.

Instead of neurons, LSTM network have memory blocks connected through layers.

A block has components that make it smarter than a classical neuron and a memory for recent sequences. A block contains gate that manage the block's state and output. A block operates upon an input sequence, and each gates that manage the block's state and output. A block operates upon an input sequence, and each gate within a block uses ths sigmoid activation units to control whether it is triggered or not, making the change of state and addition of information flowing through the block conditional.

There are three type of gates:
1. Forget gate: conditionally decides what information to throw away from the block.
2. Input gate: conditionally decides which values from the input to update the memory state.
3. Output gate: conditionally decides what to output based on input and the memory of the block.