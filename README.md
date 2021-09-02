# BrainTumor_classification by PyTorch
Using Kaggle Brain MRI Picture, Making classifier by pytorch


### Datasets
https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri?select=Training


### Data(Image) Preprocessing
Using opencv, cropped the background except brain image.
made a bounding box with opencv contouring.


### Using Pre-Trained Model with Transfer Learning
I made fully connected layer and classifier by myself.
- ResNet 50
- VGG 16
- mobilenet --> best model TEST ACC 77.4%
