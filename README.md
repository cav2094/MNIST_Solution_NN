# MNIST_Solution_NN : Teaching a computer to recognize handwritten digits from the famous MNIST dataset.
Ever wondered how a computer learns to read? This project demonstrates the process by building a neural network that deciphers handwritten digits. It walks through a complete deep learning workflow in TensorFlow/Keras, achieving 98.6% accuracy and showcasing how machines can learn to recognize patterns just like we do. 

# Summary 
This notebook builds and evaluates a neural network to classify handwritten digits from the MNIST dataset. The process begins by loading and preprocessing the data, which includes normalizing pixel values and reshaping the images. A sequential model with three hidden layers is constructed using TensorFlow/Keras, incorporating techniques like Batch Normalization and Dropout to prevent overfitting.

The model is trained for 30 epochs, and the best-performing version is saved. Finally, the model's performance is thoroughly evaluated on unseen test data, achieving an accuracy of 98.6%. The notebook concludes by visualizing the model's predictions, including a confusion matrix and examples of correctly and incorrectly classified digits. This project demonstrates a complete workflow for a standard deep learning task.

# Example of MNIST Data-set
![IMAGE ALT TEXT HERE](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/MNIST_dataset_example.png/640px-MNIST_dataset_example.png) 



# Setup
Run Locally
To run this project, clone the repository and use Conda to create the environment and install the required packages.

Clone the repository:

```Bash

git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```
Create and activate the Conda environment:

```Bash


conda create --name MNIST_NN python=3.9 -y
conda activate MNIST_NN
```
Install dependencies:

```Bash


conda install numpy
conda install tensorflow -c conda-forge
conda install matplotlib -c conda-forge
conda install scikit-learn
conda install seaborn -c conda-forge
conda install jupyter
```

