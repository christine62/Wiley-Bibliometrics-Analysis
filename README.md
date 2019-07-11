# Wiley-Bibliometrics-Analysis
We are looking for methods to identify future leading authors in a specific scientific field.
# Data 
## Data Collection
The articles data is downloaded from Web of Science (core collection) under the topic of Biomaterials from 1990 to 2019 and saved as txt files.
[Web of Science](https://clarivate.com/products/web-of-science/)
![alt text](https://github.com/christine62/Wiley-Bibliometrics-Analysis/blob/master/image/web%20of%20science.png?raw=true)
[Concatenate the txt files to dataframe and keep the meaningful columns.](https://github.com/christine62/Wiley-Bibliometrics-Analysis/blob/master/code/concatwos.ipynb)
## Data Cleaning
Remove invalid records.
## Exploratory Data Analysis
![alt text](https://github.com/christine62/Wiley-Bibliometrics-Analysis/blob/master/image/number%20of%20publications.png?raw=true)
## Impact Factor
**Impact Factor** is used to reflect the average number of citations divided by the total number of articles post on the journal recently. IF is frequently used as a proxy for relative importance of a journal. 
![alt text](https://github.com/christine62/Wiley-Bibliometrics-Analysis/blob/master/image/if.png?raw=true)   
[Merge the impact factor to dataset.](https://github.com/christine62/Wiley-Bibliometrics-Analysis/blob/master/code/merge%20impact%20factor.ipynb)
## [Author Dataset Construction](
Our research is about authors, we are trying to build the authors dataset. And considering timeliness, we will only keep authors who have publications from 2010 to 2017.
![alt text](https://github.com/christine62/Wiley-Bibliometrics-Analysis/blob/master/image/authors.png?raw=true)

