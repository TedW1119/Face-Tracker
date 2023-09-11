# face_detection

## Table of Contents

### Setup and Get Images
1.1 Install Dependencies
1.2 Collect Images With OpenCV

### Review Dataset and Load Images to TensorFlow
2.1 Import Dependencies
2.2 Limit GPU Memory Growth
2.3 Load Images to TensorFlow Data Pipeline
2.4 View Raw Images with Matplotlib

### Partition Unaugmented Data
3.1 Randomly split data into train, test and val
3.2 Move the Matching Labels

### Apply Image Augmentation on Images and Labels using Albumentations
4.1 Setup Albumentations Transform Pipeline
4.2 Load a Test Image and Annotation with OpenCV and JSON
4.3 Extract Coordinates and Rescale to Match Image Resolution
4.4 Apply Augmentations and View Results

### Build and Run Augmentation Pipeline
5.1 Run Augmentation Pipeline
5.2 Load Augmented Images to TensorFlow Dataset

### Prepare Labels
6.1 Build Label Loading Function
6.2 Load Labels to TensorFlow Dataset

### Combine Label and Image Samples
7.1 Check Partition Lengths
7.2 Create Final Datasets (Images/Labels)
7.3 View Images and Annotations

### Build Deep Learning using the Functional API
8.1 Import Layers and Base Network
8.2 Download VGG16
8.3 Build an instance of Network
8.4 Test out Neural Network

### Define Losses and Optimizers
9.1 Define Optimizer and Learning Rate
9.2 Create Localization Loss and Classification Loss
9.3 Test out Loss Metrics

### Train Neural Network
10.1 Create Custom Model Class
10.2 Train
10.3 Plot Performance

### Make Predictions
11.1 Make Predictions on Test Set
11.2 Save the Model
11.3 Real Time Detection
