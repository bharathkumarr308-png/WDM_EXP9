### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 15/5/2025
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
<img width="1823" height="1090" alt="Screenshot 2026-05-15 114712" src="https://github.com/user-attachments/assets/c271b458-b545-444c-9363-2fba2be6b718" />
<img width="1841" height="1156" alt="Screenshot 2026-05-15 114704" src="https://github.com/user-attachments/assets/2ed26f3e-ec67-4436-92e9-a0d8a4bf177f" />
<img width="1918" height="1198" alt="Screenshot 2026-05-15 114644" src="https://github.com/user-attachments/assets/20fac3d2-168a-4a97-b624-a58c7cff1538" />


### Result:
Thus, the preprocessing technique on twitter data in Rapidminer has been implemented.


