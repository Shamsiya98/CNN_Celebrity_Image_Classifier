# CNN_Celebrity_Image_Classifier
Celebrity Image Classifier Model using CNN
Summary
The model used to classify the given images is Convolutional Neural Network (CNN). The model architecture consists of three convolutional layers with max-pooling, along with dropout layer and flattening layer. Here, the dropout layer contains the dropout rate of 0.2 which implies 20% of the input units will be dropped out during training. After that, dense layers are added to the model, two with ReLU activation function and the other layer with softmax activation which helps in multiclass classification. The sparse categorical crossentropy loss, accuracy and Adam optimizer is used to evaluate the model.
Training process
Data Loading and Preprocessing:
•	Celebrity images of Lionel Messi, Maria Sharapova, Roger Federer, Serena Williams and Virat Kohli are loaded and resized to (128, 128) pixels.
•	The dataset is divided into training and testing sets.
Model Architecture:
•	CNN model is created with convolutional layers, max pooling layers, dropout layer and dense layers. Also, the model is compiled with Adam optimizer and sparse categorical crossentropy loss.
Training:
•	With a batch size of 32, the model is trained for 20 epochs using the training set.
•	Training progress is calculated, along with accuracy and loss.
Evaluation:
•	In evaluation process, accuracy and loss are calculated using graphs.
Model Prediction:
•	The trained model is used to predict labels on the test set.
•	Also, the predictions and actual labels are stored in a CSV file 
Critical Findings
•	Accuracy of the model is evaluated which indicates the model's ability to generalise to new data.
•	Changing the learning rates, dropout rates or the model architecture will some how improves the accuracy.
