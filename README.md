# MachineLearning_Model
So on this project, we have a developed model designed to detect images and identify the specific painting that a user is showcasing. The model incorporates a transfer learning approach, leveraging the EfficientNetB0 model. We enhance our accuracy through fine-tuning methods. And then we train our model with 65 epochs and after that we got result like this:![Accuracy and Loss](https://github.com/user-attachments/assets/e9e11583-939d-441f-9a6f-0805ab5d2d41) 

After we got that result, we trained 10 epoch again for fine tuning. Overall the result will like this: ![Screenshot 2024-12-03 104753](https://github.com/user-attachments/assets/b9149768-ebbe-46a1-b9f0-cbae8eec671a)

# Confusion Matrix
With the confusion matrix, we can determine the predict value with the actual value. The confusion matrix will be like this:![Confussion Matrix](https://github.com/user-attachments/assets/40e05b3e-15aa-472e-b006-9a60ee7bd0a1) 

# Function Dependencies
|  Library |  Version|
|--------|--------|
| Tensorflow | 2.17.1 |
| Keras | 2.17.1 |
| Matplotlib | 3.8.0 |
| Numpy | 1.26.4 |
| Pandas | 2.2.2 |
| Seaborn | 0.13.2 | 

# CNN
A basic model is built using Convolutional Neural Networks (CNN) as a foundation. CNN is used to recognize complex visual patterns in images, helping in the classification and recognition of objects in images on paddy disease classification

# Transfer Learning with EfficientNetB0
The implementation of transfer learning is carried out using EfficientNetB0, a well-known model architecture in image processing. EfficientNet is used to utilize the knowledge that has been previously obtained from pre-trained models and perform fine-tuning to improve model performance on painting datasets.

# Training, Fine-Tune and Training configurations
The model achieved 95% accuracy with an exceptional accuracy validation rate. Also, this model achieved a 13% loss and 18% loss validation rate. The model was then implemented in TensorFlow format and converted to a tflite model for ease of use on lighter platforms such as mobile devices. While important metadata is embedded in the model for additional information.
