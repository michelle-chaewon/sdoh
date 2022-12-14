# Code descriptions
tweet collection.ipynb - we first collected tweets using a set of keywords related to breast cancer and screening behaviors (e.g., mammogram, breast self-exam, breast MRI, breast x-ray, etc.).  

user location.ipynb - because user location is required for SDOH anaylsis, we collected user coordinates and/or free-text location data  

data preprocessing.ipynb - to build HBM classifiers, we preprocessed tweet text.  

classifier_hbm.ipynb - using 6,000 annotated tweets, we built classifiers that identify tweets related to HBM and its contructs (i.e., severity-related, susceptibility-related, benefit-related, barrier-related). A classifier of each construct followed the same code as shown in classifier_hbm.ipynb.  

US only.ipynb - because this project aims to validate the results with BRFSS data (state-based), we filtered the data to include US locations only (following lexical patterns)  

user location.ipynb - we collected a subset of user profile data to examine whether SDOH factors can be identified from user profile section.
