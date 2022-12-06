# Project_11_Dental_Anomaly_Detection

### Goal: Apply computer vision model to predict dental anomalies(multi-class) in X-ray images

### Data Profile
224 of labeled images are panoramic images, and 182 images are bitewing images

### Data Preprocessing
- Create a virtual conda environment call hu_tfod
- Apply CLAHE Image preprocessing technique
- Convert image label from Yolo TXT format to Pascal XML Fomart
- Randomly split data to 80% train 20% test

### Model Application
Apply 3 pre-trained object detection models (SSD Mobilenet, SSD Resnet, EfficientDet)
Tune models with SGD Optimizer and Adam Optimizer
Tune Number of ephchs, batches, and training steps 

### Model Evaluation
Evaluate model using precision
Achieved 83% prediction accuracy on existing fillings, 92% accuracy on root canal treatment, and 92% accuracy on crowns


