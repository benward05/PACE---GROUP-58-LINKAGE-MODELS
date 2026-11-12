Please note: 
THE FILES IN ".gitignore" are the datasets : 
- target_train.csv
- target_test.csv
- shadow_train.csv
- shadow_test.csv

It is important that you download these files from Microsoft Teams beforehand. Or else the file will not run.
They can go into the same location as to where you clone the repository, because they are in .gitignore so they will not be picked up when you are pushing.

NOTE THAT THE IMPORTS ARE NOT HERE. THESE ARE DEVICE DEPENDANT, YOU WILL NEED TO INSTALL THESE ON YOUR OWN. To know what imports to install, please see the first cell of the notebook file.

When running the notebook file, please skip step 3 "Generate embeddings only for train and test separately" as this is requires high computational power. 
As an alternative please scroll to the next cell labelled "Directory to store cached files" and run that instead. This cell runs the precomputed BERT embeddings provided by the sponsor MQSOC.

**Steps to run the notebook**
1. Clone the repository
2. Download the datasets from Microsoft Teams:
- target_train.csv
- target_test.csv
- shadow_train.csv
- shadow_test.csv
3. Place the files in the project root directory
4. Install required python packages.
5. Open and run the notebook.
6. Skip step 3 as advised above.
7.Run the cell directly below instead of step 3.
8. CSV and other findings will appear in the same folder where you said was the root directory.
