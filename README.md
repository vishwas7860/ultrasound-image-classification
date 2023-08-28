# ultrasound-image-classification
A deep-learning based model that is capable of classifying anatomical structure in 2D fetal ultrasound images
### dataset: `https://www.kaggle.com/datasets/vishwaskant786/2d-fetal-altrasound-images?datasetId=3668824`
### Method:
`1. Model Architecture:` The model is constructed as a sequential neural network using
TensorFlow's Keras API. It begins with two convolutional layers with 32 and 16 filters,
respectively. This is designed to capture hierarchical features in the input images.
`2. Flatten and Dense Layers:` After convolution and pooling, the data is flattened into a 1D
vector and passed through fully connected layers. This architecture is common in image
classification tasks.
`3. Training:` The model is trained using the Adam optimizer and categorical cross-entropy
loss function. Early stopping is implemented to prevent overfitting.
