# Improving-Cancer-Classification-Accuracy-using-Ensemble-Learning
The aim is to improve the cancer classification accuracy for the National Cancer Institute(NCI) Dataset, that consists of 11,486 samples into tumor and benign samples.

Pre-requirements:
1. Anaconda Jupyter Notebook 
2. Pandas, Sklearn, Numpy, Matplotlib

The project explanation can be found at the link given below:
https://youtu.be/UL7GO2DI5TQ

Steps to run the project:

1.  Download the MiRNA data and the file IDs(file_id.tsv) of each patients from the NCI cancer repository.
2.  Run the command: pytho matrix_generation.py
    This code basically intakes the MiRNA data and the file IDs of the patients and extracts the data of a particular patient for a particular cancer type and generates a different '.csv' files for each cancer types. The data includes the patients race, ethnicity,gender and age. We will further consider only eight cancer types namely breast, lung, kidney, stomach, head and neck, prostate, liver and thyroid cancer.
3.  Run the command: python predict.py
    This code takes '.csv' file as the input. Output of this code gives the classification accuracy using the data ensemble method stored in 'cancertype_accuracy.txt', important features to classify the cancer as tumorous or benign store in 'cancertype_features.txt' and also the feature importance graph stored in 'cancertype_graph.png'.
    
Project Member: Janhavi Karekar, Tamara Fernandes, Khushboo Korani
