---
layout: default
modal-id: 1
modal-id-str: vehicle_classification
date: 2023-02-28
img: project_card_1.png
alt: image-alt
category: Machine learning - Computer Vision
title: vehicle classification from images
technology: Pandas, Numpy, PyYAML, OpenCV, TensorFlow, Keras, TensorBoard, Detectron2, PyTorch, AWS (S3 and EC2), Boto3, Docker, GitHub
description: In this project, we aimed to build a computer vision model for vehicle classification using advanced machine learning techniques.<br><br>  &nbsp;&nbsp To begin, we gathered the dataset of vehicle images from an S3 bucket and wrote a Python script to format the data in a way that our Keras model could use. Next, we employed transfer learning by using a pre-trained Resnet50 model, which had been trained on the Imagenet dataset, to perform vehicle classification. By retraining all layers except for the final classification layer, we were able to adapt the model to our specific needs.<br><br>  &nbsp;&nbsp Then, we fine-tuned our model by experimenting with different hyperparameters and techniques such as data augmentation and regularization to improve its performance. To further enhance its accuracy, we decided to remove noisy backgrounds from the images using a vehicle detector to locate the car within the image and isolate it from the rest of the content. We utilized the Detectron2 framework, specifically the "R101-FPN" model, to perform this task. By training our fine-tuned model on the resulting cropped images, we improved classification accuracy over our baseline and fine-tuned models trained on full-size images. <br><br>  &nbsp;&nbsp Throughout the project, we containerized all components in Docker, enabling easy deployment and scalability. We also utilized Git, GitHub, and ssh to facilitate the efficient use of local and cloud shared resources. In conclusion, this project not only showed us the power of transfer learning and advanced machine learning techniques but also highlighted the significance of efficient development processes and collaboration in ML projects.
---
