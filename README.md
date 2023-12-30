# ad-tau-prediction

Authors: Carlos Ayala Bellido & Ardo Nashalian

Titled officially as "Determining Neural Region of Interests' Relationship to Cognitive Impairment 
Symptoms Using Tau Scans", this Github repo serves as an extension of our final project from the 
Fall 2023 edition of the Stanford University course PSYC 221: Machine Learning for Neuroimaging 
(ML4N). The purpose of this project extends from our shared interest in the improvement of
predictions with regards to Alzheimer's Disease (AD). 

## Setup Instructions
To run this project, we recommend using Python 3.9.1, as this is the local environment we've been 
testing this code in. Running the notebook in Google Colab should be fine as well, but may require 
additional adjustments to the libraries. The specific libraries and packages being used are listed
(with the designated versions) in requirements.txt. For running the individual Python files, we
recommend running these files through a Conda environment. Steps to do so are as follows:
1. Create a Conda environment: conda create -n adtaupred python=3.9.1
2. Activate the Conda env: conda activate adtaupred
3. Install pip: conda install pip
4. Use pip to install the proper packages: python -m pip install -r requirements-conda.txt