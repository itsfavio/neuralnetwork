# neuralnetwork
Keras Neural Network
To use the pretrained model, import the H5 Python library. Before using the pretrained model, your data needs to be scaled. The model's input needs to be in a Python
data frame and in the shape (nx5), where n is the nth number of rows and 5 is the number of columns. Make sure that input data is in the correct order, i.e the columns need
to match the corresponding inputs otherwise the model's predictions will be completely invalid. To aid in the standardizing process, use the standardizing function I have
included under the Standardizing folder. The model's output will be also be scaled so use the Unscale function that is also in the Standardizing module. 

Note:
The model is still in it's early stages as more data is needed to yield more accurate results and combat overfitting.
