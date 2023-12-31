# Summary  

This notebook is based on the notebook from the Udemy course "Complete ML & Data Science Bootcamp 2023." This Notebook is included in this project as "end-to-end-heart-disease-classification.ipynb"

The goal of this notebook is to correctly determine if a patient has heart disease based on certain information such as age, sex, chest pain type, and cholesterol. Here we are following the same methodology as the course but using a different dataset to compare to the dataset used by the original project. The data set(s) are collected from the UCI ML Repository.  

The model used for all experiments was "LogisticRegression."

The best results based on Recall, Accuracy, and F1 Scire is the original dataset (303 rows), with the following scores:  

- Acc: 78.69%  
- Recall: 96.67%  

The best experiment based on Precision is the New/Full dataset with some columns removed (920 rows).
The score is 74.31% vs 70.73% of the original data set.  


# How to Run  
1. Download the most recent version of this project
2. Ensure Conda and Jupyter is installed on your system
3. Create a new conda environment from the env.yml file
4. Activate the conda environment and run the command `jupyter lab` or `jupyter notebook`
5. Run the Notebook!

# Extension  

This is a work in progress, the next step is to compare the TP, TN, FP, and FN counts.  

A possible extension to this is to find a different model to train to try to get better results or to try transfer learning.  
