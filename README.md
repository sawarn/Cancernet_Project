# Cancernet_Project
The given Deep Learning model aims on identifying the malignancy or benign ency of cancer on the given image of different parts of cell.

The dataset can be downloaded from kaggle under the name of IDC_regular_ps50_idx5 which is a dataset of over 200000 images already structured into zero and one format specifying negative and positive cancer results.
We have used this dataset and then seperated into randomly training,testing,validation and then processed it as per our needs.

The model does a simple job of identifying the image as negative or positive during its training period by simply stripping the labels from the name of the folders and then using them as training labels and further training the model.

