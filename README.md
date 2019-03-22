# NDSC - A-Team

NOTE: All notebooks assume that images are extracted to
- ./data/images/beauty_image/
- ./data/images/fashion_image/
- ./data/images/mobile_image/

## Notebooks

### data-cleaning.ipynb

Clean labelled data by standardizing image paths and inserting categories into titles

### image-analysis.ipynb

Train an image model using a CNN based on ResNet50

### nlp-analysis.ipynv

Fit a language model based on AWS_LSTM by using all tokenised vocab provided in the labelled set
Use this language model to train a NLP model

### predict.ipynb

Make predictions by getting the argmax of separate predictions from image and nlp models