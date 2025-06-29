🦋 Butterfly Species Classification using CNNs

📌 Overview
This project was developed as part of a competition for Students, with the goal of applying Convolutional Neural Networks (CNNs) to classify butterfly species based on images.

In this contest, we utilized several popular CNN architectures such as AlexNet, ResNet, InceptionNet, and MobileNet to solve the butterfly image classification task.

The objective is to build a CNN model that can predict the species of butterflies from unseen images provided in a test set. The training set contains 5000 labeled images of 75 different butterfly species, and the test set contains 1499 unlabeled images.

🗂️ Dataset Description
The dataset includes:

75 butterfly species (classes)

5000+ labeled images for training

Each image belongs to exactly one species

Labels are provided in a CSV file (Training_set.csv)

You need to predict labels for the test set (test folder), and submit your predictions in the format specified by sample_submission.csv

🧠 CNN Architectures Used

In particular, I trained and fine-tuned an EfficientNet model, which achieved a high accuracy of 95% on the validation set.
