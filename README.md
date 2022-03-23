# Boolean Retrieval System
A Booloean information retrieval system with spelling correction and wildcard query handling. 

## Features

1. Returns list of documents that satisfies the boolean query. The boolean operations allowed are AND, OR and NOT.
2. Preprocessing of text in the documents includes:
    1. Stopword Removal
    2. Lemmatization
3. Other features are:
    1. Wildcard Query Handling 
    2. Spelling Correction

## Tech-Stack Used

1. Python
2. NLTK Library

## Set-Up Procedures
* Download the data-set from this link : [Data-set](https://github.com/ishitaa27/BooleanRetrievalSystem/blob/main/shakespeares-works_TXT_FolgerShakespeare.zip)
* Unzip the file and upload all the documents in a folder called 'Assignment' on your google drive
* Open the [IR.pynb file](https://github.com/ishitaa27/BooleanRetrievalSystem/blob/main/IR.ipynb) on google colab and run each cell.

### Test Cases
* Some possible test cases that can be run to test the code:
```
William and barbara
```
```
Will* and not barb*
```
```
billiam and barbara
```

## Team Members

* Ishita Menon
* Nived Damodaran
* Jayaram J
