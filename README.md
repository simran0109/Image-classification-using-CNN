Image Classification using Deep CNN in Keras.

A Convolutional Neural Network (CNN) is a type of deep neural network commonly used for processing and analysing visual data such as images. It's designed to automatically and adaptively learn hierarchical patterns and features from the input data.

Few important things done in this code:
1. Image classification using Deep CNN in Keras.
2. The dataset used is cifar10: 
 The CIFAR-10 dataset is a collection of 60,000 32 x 32 color images in 10 classes, with 6,000 images per class.
 0:'airplane', 1:'automobile', 2:'bird', 3:'cat', 4:'deer', 5:'dog', 6:'frog', 7:'horse', 8:'ship', 9:'truck'
3. Used LabelBinarizer for one hot encoding
4. Used early_stopping, model_checkpoint
 - When the performance on the validation set starts to degrade (i.e., the validation loss increases), early stopping interrupts the training process before the model overfits the training data. By stopping the training early, early stopping helps prevent the model from memorizing noise in the training data and allows it to generalize better to unseen data.

-Model checkpointing is a technique used to save the model's weights (parameters) during training at specified intervals or whenever the model achieves the best performance on the validation set. By saving the model's weights periodically, model checkpointing allows you to keep track of the model's progress throughout training and recover the best-performing model if training is interrupted or if you need to evaluate the model's performance at different points during training. This helps ensure that you have access to the best version of the model for inference or further analysis.
