# Project: 
### Data folder

The data directory contains data used in the analysis. This is treated as read only; in paricular the R/python files are never allowed to write to the files in here. Depending on the project, these might be csv files, a database, and the directory itself may have subdirectories.

Since the dataset we use in our project is too large to upload on Github, we decided to upload it on Google Drive and could be downloaded at https://drive.google.com/file/d/1KS2roQgvcd8dGJLcXhNxyTMwowG9x-BP/view?usp=sharing. 

reduced2.csv contains transaction history for all customers for a period of at least 1 year prior to their offered incentive, and we will only use a reduced amount of transaction data (~600MB), selecting transactions from chain 2, 4 and 8. 

trainHistory.csv contains the incentive offered to each customer and information about the behavioral response to the offer.

testHistroy.csv contains the incentive offered to each customer but does not include their response. (We did not use this data in the project)

offers.csv contains information about the offers.
