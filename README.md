## Schneider Electric Datascience Hackathon - Satellite Imagery Classification
This project is about image classification of satellite imagery, which was a problem presented in the Schneider Electric datascience hackathon. Our team has performed data analysis and visualizations, trained a Deep Convolutional Neural Network called EfficientNetV2S, and achieved competitive results.

Problem
The problem was to classify satellite images into one of the four possible classes:

Barren land
Trees
Grassland
Other
The dataset provided by Schneider Electric had a total of 4000 images, 1000 images for each class. The challenge was to train a model that could accurately classify these images.

Data analysis and visualizations
We started by exploring the dataset, checking for class imbalances, and performing some visualizations. We found that the dataset was balanced and the images had different sizes and color distributions. We also plotted some sample images for each class to get a better understanding of the data.

Model Training
We decided to use EfficientNetV2S, a state-of-the-art deep learning architecture that has shown excellent performance on image classification tasks. We trained the model on the dataset using the TensorFlow library, with a batch size of 32 and a learning rate of 0.001. We used the categorical cross-entropy loss function and the Adam optimizer.

We trained the model for 30 epochs and achieved a validation accuracy of 93%, which is competitive compared to other participants in the hackathon.

Future Steps
Our future steps include applying transfer learning using pre-trained models to further improve the model's performance. We plan to use pre-trained models such as ResNet, VGG, and Inception, and fine-tune them on our dataset.

Conclusion
In conclusion, the Schneider Electric datascience hackathon was a great experience for our team. We were able to apply our data analysis, visualization, and deep learning skills to solve a real-world problem. Our model achieved competitive results, and we look forward to applying transfer learning to further improve its performance.
