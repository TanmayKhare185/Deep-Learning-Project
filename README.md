CIFAR-10 Image Classification with TensorFlow
This project demonstrates an end-to-end deep learning pipeline for image classification using the CIFAR-10 dataset and TensorFlow/Keras. It includes data loading, preprocessing, CNN model building, training, evaluation, and visualization of predictions.

🚀 Features-
Loads and normalizes CIFAR-10 dataset

Defines a CNN using TensorFlow Keras Sequential API

Trains the model with accuracy/loss plots

Evaluates on the test set

Predicts and visualizes sample outputs

🧠 Model Architecture-
The CNN includes:

3 convolutional layers with ReLU activations and max-pooling

Flattening and dense layers

Softmax output for 10 class probabilities


🏁 Training and Evaluation-

Uses SparseCategoricalCrossentropy loss

Optimizer: Adam

Tracks accuracy on both train and validation sets

Final test accuracy: ~73%

📊 Results-
Accuracy & Loss Graphs
Clear upward trend in accuracy

Gradual reduction in loss, slight overfitting visible

Sample Predictions
The model is evaluated on unseen test data and predictions are visualized alongside true labels.

🖼️ Sample Output
True vs. Predicted labels are displayed using PIL & Matplotlib

Images are annotated to assess model performance visually

📌After training, run the 📚 Dataset,

CIFAR-10 is a standard computer vision dataset consisting of 60,000 32x32 color images in 10 classes, with 6,000 images per class.
