Whats included:  
    • A Python Notebook file, k_anonymity.ipynb, which contains all the code required for questions 1-6 on the pset. It also contains various assert statements to check whether the functions are doing the k-anonymizing properly.  
    • A configuration file, config.txt, that contains the list of quasi-identifiers seperated by new lines. The k_anonymity file reads in the quasi-identifiers from this file.  
    • The dataset, mid_sample_set.csv, is NOT included. We choose to not include large datasets on github as it often complains. The dataset should be in the directory directly outside of the directory with the code to be imported correctly.  

Running the code:  
    • Ensure that the dataset is in the directory directly outside of the directory with the code.  
    • We recommend Jupyter Notebooks to run the Python notebook files.  
    • Run through k_anonymity.ipynb file line by line. Shift+enter executes a code block in Jupyter Notebooks.   
    
Testing:  
    • There is no seperate file for testing. An assert statement is placed after the construction of the k-anonymous datasets to check that it is indeed the required level of k-anonymity.