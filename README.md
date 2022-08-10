# StatementMasher

Here's what you need in your folder:

* main.py - the main program
* Data.xxx.csv - where "xxx" is a unique identifier for that bank statement, like the last 4 digits, etc. the indentifier will be used in the output.
You can have as many bank statements (and therefore different Data.xxx.csv files) as you want. 
* fileinputs.csv - a list of all the Data.xxx.csv files, with a T_sign to normalize "polarity" of credits and debits in the amount columns of each data file
* DictionaryLabels.csv - this is used by main.py to create a dictionary to normalize all different statement column names into universal names for the output file.
Also, in the Github repo you'll see two example output files. You do not need those in your folder to start. 

To run the program, if terminal prompt is >>, then enter:   >>python3 main.py
