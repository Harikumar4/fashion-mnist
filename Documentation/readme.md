### 1. Introduction and Objective

**Dataset Description:**  
The Fashion MNIST dataset contains grayscale images of 10 different categories of clothing items, including T-shirts/tops, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots. Each image is represented by 784 pixel values, and the dataset includes a total of 10 classes. The train dataset contains a label column indicating the class of the item, along with 784 pixel values for each image.

**Objective:**  
The objective of this project is to build a neural network model that accurately classifies images in the Fashion MNIST dataset into one of the 10 categories: T-shirts/tops, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, or ankle boots.

### 2.Data Preparation
**Loading the data**
The training and testing data were loaded from CSV files, which contained pixel values and labels for each image. The pixel values, originally spread across multiple columns, were separated from the labels and reshaped into their original 28x28 pixel dimensions to match the format required for model input.

**Data Normalization**

To ensure that the data is in an appropriate range for the neural network, the pixel values were scaled down to a range between 0 and 1. This normalization step is important for improving the efficiency and accuracy of the model during training.

**Training and Validation Data**

The training data was optionally divided into two parts: one for training the model and the other for validating its performance during development. This split helps in assessing how well the model is likely to perform on unseen data.
