## Neural networks from scratch

### Description

This project is about implementing a neural network completely from scratch. The implementation can be found in the file `NeuralNetwork.py`. 

The file `TrainingAndEvaluation.py` has utility functions for training and evaluating the neural network, as well as plotting a confusion matrix. <br> 
The file `NetworkOptimization.py` is used to do hyperparameter optimization. <br>
The file `main.py` is used to test the implementation. <br>

Additionaly, there is the file `SimulatingLogicFunctions.py` which was used in the begginning to train a single layer perceptron to simulate logic functions. 

### Running the code

Just run the main method inside `main.py`. After running it, the predictions to features inside the file `unknown.txt` will be saved in the file `predictions.txt`.
For running cross-validation and performance over training and validation sets, lines 26 and 37-38 in the main method should be uncommented respectively. There are comments about this in the code as well.

**Libraries used in this project:** Numpy, matplotlib, scikitlearn.


