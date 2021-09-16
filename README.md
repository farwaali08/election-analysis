# election-analysis


![alt text](https://github.com/farwaali08/election-analysis/blob/b1b9ead30a91209ad88af31be0546a19e972f3fd/analysis/Counties.png)
> Modified from [Source](https://coloradosun.com/2021/06/09/colorado-vaccination-rates/)

## Performing an Election Audit with Python

All the relevant files for this analysis can be found within the "analysis" folder. Please refer to the quick links below:

[Python "Challege" Code](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/PyPoll_Challenge.py)

[Election Results Text File](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/election_analysis.txt)

[Election Data (CSV)](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/election_results.csv)



### **OVERVIEW**

This project is in collaboration with the "Colorado Board of Elections" to complete an audit of a recent congressional election. A [script](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/PyPoll_Challenge.py) was created to run an analysis on electoral data, with the main objective being to generate a vote count report with the following information:

1. The total number of votes cast

2. A complete list of candidates who received votes

   1. The total votes received for each candidate 

   2. The percentage of votes won by each candidate

3. The winner of the election based on the popular vote


The original script was modified to include regional statistics as well:

1. The voter turnout for each county

2. The percentage of votes from each county out of the total count

3. The county with the highest turnout


### **RESOURCES**

Software: Python 3.9.7, Visual Studio Code 1.60.0 

Data: [election_results.csv](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/election_results.csv)

### **RESULTS**

The election results are below:

![alt text](https://github.com/farwaali08/election-analysis/blob/95a3750fe8da32aea512a84f10e19d1302f18898/analysis/election%20results.png)

The script is programmed to generate a text file of the results, which can be found in the "analysis" folder, or by clicking the link in the introduction. The data indicates that:

* 369,111 votes were cast in this election

* The votes were allocated between the following candidates:

  - Charles Casper Stockham : **23.0%** (85, 213)
  
  - Diana DeGette:            **73.8%** (272,892) 
  
  - Raymond Anthony Doane:    **3.1%** (11,606) 

* Diana DeGette is the winner of the popular vote


Regionally, the largest turnout (by number) was observed in Denver county--nearly 83% of all votes cast in this election were cast in Denver.

### **SUMMARY**

