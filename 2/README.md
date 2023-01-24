# Module 20 - Neural Networks

## Module Supplement

### 20.2.3 - Train and Test a Basic Neural Network

- Your graph of the `loss` and `accuracy` will looks different than the module images. You will get a different output each time you run the algorithm.

- When you get to the question `Looking at the loss and accuracy plots in the images above, how many epochs did it take before the model started to fit the training data with high success?` - This answer may not be as obvious depending on the result of your algorithm. To answer this, go off of the images provided in the module. 

### 20.6.1 - Checkpoints Are Not Just for Video Games

- When the module states to `open our "DeepLearning_Tabular" (or whatever similar name you may have used) notebook and rerun all of the code` they are referring to the notebook you were using for section 20.4.4

### 20.6.2 - For Best Results, Please Save After Training

- When you are exporting your model, be sure to use the name of your model you are wanting to export
    - ```python
        # Export our model to HDF5 file
        <modle_variable_name>.save("trained_attrition.h5")
    - ex) 
        ```python
            nn.save("trained_attrition.h5")

- - -

## Class Material Reviews

### Class 1
- An overview of a neural network was provided in Lesson **20.1.1**
- The perceptron model was covered in Lesson **20.1.2**
- The basic components of a neural network model were covered in Lesson **20.1.3**
- The TensorFlow Playground was covered in Lesson **20.1.3**
- The Keras module and the two Keras classes, Sequential and Dense, were covered in Lesson **20.2.1**
- Building a basic neural network was covered in Lesson 20.2.2, and training the model was covered in Lesson **20.2.3**

### Class 2
- Model optimization was covered in Lesson **20.2.5** and Lesson **20.2.6**
- An overview of one-hot encoding and "binning" was provided in Lesson **20.3.2**
- An overview of deep learning and conceptualizing a deep learning model with the TensorFlow Playground was covered in Lesson **20.4.1**
- Using one-hot encoding was covered in Lesson **20.3.3** and Lesson **20.4.2**
- Standardizing numerical values using `StandardScaler()` was covered in Lesson **20.3.4**, Lesson **20.4.2**, and Lesson **20.4.3**
- Real design, practice, and evaluation of a deep learning model were covered in Lesson **20.4.4** and Lesson **20.4.5**

- - -

## Challenge Instruction Supplement

### Deliverable 1

- Be sure to change the path in your starter code notebook to the proper path where your `charity_data.csv` is located

- In order to `# Visualize the value counts`, you need to plot the density of the value counts








