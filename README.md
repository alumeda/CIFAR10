# CIFAR10


**Overview**
This program implements a convolutional neural network (CNN) using PyTorch to classify images from the CIFAR-10 dataset into 10 different categories. It first imports and preprocesses the dataset, applying transformations such as random horizontal flipping, color adjustments, tensor conversion, and normalization. The CNN consists of multiple layers, each involving max pooling, batch normalization, ReLU activation, and dropout to extract relative images and reduce overfitting. The extracted features are flattened and passed through fully connected layers before producing 10 output values corresponding to the possible image classes. The model is trained using the Adam optimizer and cross-entropy loss over multiple epochs, with its performance evaluated on the testing dataset throughout the training process. Finally, the program compares the model's classification accuracy before and after training, generating confusion matrices to visualize its performance. 


**Object Categories:** (6,000 images per category)
- Airplanes
- Automobiles
- Birds
- Cats
- Deer
- Dogs
- Frogs
- Horses
- Ships
- Trucks
Each image is a 32x32 RGB image.


**Skills:**
- Machine Learning Concepts
- Deep Learning
- PyTorch
- matplotlib
- sklearn
- Data Analysis
- Data Processing
- Machine Learning Model Training and Development
