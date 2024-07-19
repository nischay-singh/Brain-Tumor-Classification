# Brain Tumor Classification

This app uses a machine learning model using convolutional neural networks that I created using a dataset of MRI scans(https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset). The model has an accuracy of 96.6% and can classify an image as either having a meningioma, glioma or a pituitary tumor, or no tumor. I then used Flask to create a simple web app to use the model.

## Instructions to install to your local machine
Make sure to have the latest release of python and pip installed before attempting to run this project. Once in the desired directory, run the following commands to start the web app
```
git clone https://github.com/nischay-singh/Brain-Tumor-Classification.git
pip install App/requirements.txt
python app.py
```
