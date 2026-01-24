# AnalysisNotebookUsage
This notebook contains the code for the Design a Study project of the course Empirical Methods in Software Engineering (2IMP40) from group 16. This is a course from the Eindhoven University of Technology.

## Abstract from the Project Paper


## Reproducability
To rerun the notebook, follow these steps. 

### Step 1: Download the Data
The data can be found in the paper: T. Nakamaru, T. Matsunaga, and T. Yamazaki, ``Jupyter Notebook Activity Dataset,'' in Proc. IEEE/ACM 22nd Int. Conf. Mining Software Repositories (MSR), 2025, pp.~581--585, doi: 10.1109/MSR66628.2025.00091 under the link: https://zenodo.org/records/13357570 

Only the following file needs to be downloaded from this link:
- rsds-20241113.zip: Collection of SQLite database files

Unzip the file and put it in the same directory as the notebook. 

To reproduce the second method for RQ1 you need to download the train.csv file and test.csv file from this link: https://www.kaggle.com/competitions/titanic and put it in the same directory as the notebook.

### Step 2: Download all Packages needed
For notebook rq1 you need to download the following packages:
- pandas
- sqlite3
- pathlib
- json
- nbformat
- nbclient
- hashlib
- pprint

For notebook rq2 you need packages:
- pandas
- dataclasses
- typing
- sqlite3
- json
- numpy
- matplotlib
- sklean (scikit-learn)
- scipy
- seaborn
- itertools

### Step 3: Run the Notebook
The notebook should now be able to run!