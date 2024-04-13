### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 13/04/2024
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.
### Output:
### Read Excel Operator:
![image](https://github.com/NITHISHKUMAR-P/WDM_EXP9/assets/93427017/1e07179f-3c86-483a-950b-db7ff4335d53)
### Excel File:
![image](https://github.com/NITHISHKUMAR-P/WDM_EXP9/assets/93427017/7379f0b8-3a80-42b7-b8d8-134312342f39)
### Select Attributes Operator:
![image](https://github.com/NITHISHKUMAR-P/WDM_EXP9/assets/93427017/8244db3d-ed6f-42c1-8b7c-68bd6ce67c76)
![image](https://github.com/NITHISHKUMAR-P/WDM_EXP9/assets/93427017/0f43a15e-bd4a-4edc-a744-19fa6ee54a0a)
### Replace Operator:
![image](https://github.com/NITHISHKUMAR-P/WDM_EXP9/assets/93427017/ef6806dc-edd6-4234-a3ae-e391ada7daad)
![image](https://github.com/NITHISHKUMAR-P/WDM_EXP9/assets/93427017/ed66c4d8-422a-46db-ad5f-851941bd5039)
### Process Documents from data Operator:
![image](https://github.com/NITHISHKUMAR-P/WDM_EXP9/assets/93427017/c4793f7e-a059-4ee1-89aa-b8e2b4dcf106)
![image](https://github.com/NITHISHKUMAR-P/WDM_EXP9/assets/93427017/395058a5-cadb-41f7-bf1a-90de46551bbf)
![image](https://github.com/NITHISHKUMAR-P/WDM_EXP9/assets/93427017/8110d535-a70d-4bd7-8bac-c4b47eaa8785)

### Result:
Thus, the data from twitter is preprocessed successfully using rapidminer.
