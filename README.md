# Schizophrenia

## Improving the Text of the Schizophrenia Detection Project

In this project, we utilize a dataset for the detection of schizophrenia. Initially, we convert the dataset into images, such that each feature is mapped to an individual image. These images are then fed into our Convolutional Neural Network (CNN). To prepare the dataset, we leverage the MNE library.

### Dataset Splitting

The dataset is divided into two parts: 80% for training and 20% for testing. The training set consists of approximately 500 images, which are equally divided into two categories: 250 healthy images and 250 images of patients. The testing set is also divided in the same manner.

### Data Augmentation and Overfitting Prevention

To increase the diversity of the training data and prevent overfitting, we employ data augmentation techniques. Additionally, we utilize a pre-trained CNN called EfficientNet and fine-tune it for our dataset using transfer learning. This process allows us to adapt a previously trained network to the new dataset.

### Training Process and Results

During the training process, the training dataset is fed into the network, and the model learns from it. Ultimately, the final training accuracy reaches 97%, indicating the model's excellent performance in detecting schizophrenia.

### Conclusion

By employing image processing techniques, deep learning, and transfer learning, we have successfully developed a powerful model for schizophrenia detection that can assist physicians in the early diagnosis of this condition. This advancement has the potential to improve the quality of life for patients and facilitate their treatment process.
