# Mask Detection based on Create ML

### Project Collaborators：

* [Michael](https://github.com/O0OMichael)
* [Alex](https://github.com/AlexanderHe-CHAO)
* Steven
* Hanson

## Overview
Our intention is to build an automated face mask detection model to test whether people wearing masks appropriately. The model can be deployed in iOS system.
## Project Design

### This project conducts model training based on [Create ML](https://developer.apple.com/documentation/createml).

![Training Model](https://github.com/AlexanderHe-CHAO/Markdown-Pictures/raw/main/Training%20Model.jpeg?raw=true)

### The App used in the project comes from the Sample Code of Apple developer website named [Recognizing Objects in Live Capture](https://developer.apple.com/documentation/vision/recognizing_objects_in_live_capture).

### The data set comes from [Kaggle](https://www.kaggle.com/andrewmvd/face-mask-detection) and includes 853 images.

![Kaggle Dataset Face Mask](https://github.com/AlexanderHe-CHAO/Markdown-Pictures/raw/main/Kaggle%20Dataset%20Face%20Mask.png?raw=true)

### The dataset is divided into three classes:

* Wearing Mask
* Not Wearing Mask
* Wearing Mask Improperly

![three classes](https://github.com/AlexanderHe-CHAO/Markdown-Pictures/raw/main/Three%20Classes.png?raw=true)

### Dataset are Labeled by using IBM's [Cloud Annotations](https://cloud.annotations.ai/buckets/alexandersurpass?location=us-standard) feature.

![IBM Cloud Annotations](https://github.com/AlexanderHe-CHAO/Markdown-Pictures/raw/main/IBM%20Cloud%20Annotations.png?raw=true)

### Detailed explanation of this project is in this [Video](https://youtu.be/wXzsETLjuHY).












