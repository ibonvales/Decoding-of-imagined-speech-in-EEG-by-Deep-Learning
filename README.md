**Thinking Out Loud: Unveiling Brain Oscillations in Vowel and Semantic Decoding**

This repository contains all the code and resources used for decoding imagined speech from EEG data using deep learning techniques. Below is a detailed description of the folder structure and the contents of this repository:

Folder Structure
Datos/
Contents: This folder contains all the data analysis related to model training. It includes:
Drive: Contains accuracy and F1 scores for all conditions and frequency bands.

Statistical Analysis: This subfolder includes statistical analyses for three main objectives:
Production Decoding: Comparing Rest vs. Imagined vs. Real speech.
Vowel Decoding: Analysis of the five Spanish vowels (A, E, I, O, U).
Semantic Decoding: Analysis of semantic categories such as Clothes, Animals, Musical Instruments, Food, Kitchen Items, and Body Parts.

EEG_Prepro/
Contents: This folder includes the code used with the MNE library to preprocess EEG data. It contains scripts for:
Obtaining Morlet Wavelets for all vowels, semantic categories, and types of production.
Analyzing across various brain oscillations.

DL Model: Adaptation from the work of Roy et al., (2018). Doi: https://doi.org/10.48550/arXiv.1802.00308


Additional Information
As of June 13, 2024, the preregistration for the upcoming experiment, which will commence next month, has been completed. The preregistration document, along with plans for data analysis and preprocessing, has been uploaded to this repository.
Update: This work is already finished. 

Usage
Data Analysis: Refer to the Datos/ folder for detailed analysis and results of the model training.
Preprocessing Code: Use scripts from the EEG_Prepro/ folder for EEG data preprocessing.
Statistical Analysis: Check the Statistical Analysis folder for insights into production, vowel, and semantic decoding.
How to Contribute
Feel free to fork this repository and contribute to the ongoing research. If you have any suggestions or find any issues, please open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
