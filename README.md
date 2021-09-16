# election-analysis


![alt text](https://github.com/farwaali08/election-analysis/blob/b1b9ead30a91209ad88af31be0546a19e972f3fd/analysis/Counties.png)
> Modified from [Source](https://coloradosun.com/2021/06/09/colorado-vaccination-rates/)

## Performing an Election Audit with Python

All the relevant files for this analysis can be found within the "analysis" folder. Please refer to the quick links below:

[Python "Challege" Code](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/PyPoll_Challenge.py)

[Election Results Text File](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/election_analysis.txt)

[Election Data (CSV)](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/election_results.csv)



## **OVERVIEW**

This project is in collaboration with the "Colorado Board of Elections" to complete an audit of a recent congressional election. A [script](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/PyPoll_Challenge.py) was created to run an analysis on electoral data, with the main objective being to generate a vote count report with the following information:

1. The total number of votes cast

2. A complete list of candidates who received votes

   1. The total votes received for each candidate 

   2. The percentage of votes won by each candidate

3. The winner of the election based on the popular vote


The original script was modified to include some regional statistics as well:

1. The voter turnout for each county

2. The percentage of votes from each county out of the total count

3. The county with the highest turnout


## **RESOURCES**

Software: Python 3.9.7, Visual Studio Code 1.60.0 

Data: [election_results.csv](https://github.com/farwaali08/election-analysis/blob/7d21a6e0653389dd9c168989e4d69f00f83b0ac5/analysis/election_results.csv)

## **RESULTS**

The election results are below:

![alt text](https://github.com/farwaali08/election-analysis/blob/95a3750fe8da32aea512a84f10e19d1302f18898/analysis/election%20results.png)

The script is programmed to generate a text file of the results, which can be found in the "analysis" folder, or by clicking the link in the introduction. The data indicates that:

* `369,711` votes were cast in this election

* The votes were allocated between the following candidates:

  - Charles Casper Stockham : `23.0% (85, 213)`
  
  - Diana DeGette:            `73.8% (272,892)` 
  
  - Raymond Anthony Doane:    `3.1% (11,606)` 

* Diana DeGette is the winner of the popular vote


Regionally, the largest turnout (by number) was observed in Denver county--nearly `83%` of all votes cast in this election were cast in Denver.

## **SUMMARY**

The original script was successful in delivering a rapid analysis of the election results, making it an efficient alternative to Excel, and ideal for larger data sets. 

With small modifications, the report was also able to include regional data in the output, which can provide valuable insights for future elections. For example, identifying counties with low voter turnout highlights where resources should be allocated to boost turnout in the future. 

This also demonstrates the flexibility and scalability of the the script: not only can it be used on larger data sets (or for larger elections,) some modifications can greatly expand the range of information that can be made available. One example includes determining how the candidates fared in each county (which can be done by adding a conditional ("if") statement). This in turn provides valuable insights to the candidates. 

 The script's capabilities are not limited to this election, or even congressional elections in general. For other elections types, modifying the parameters (e.g. "county" to "state") would produce similar results.

For a more thorough analysis, another suggestion would be to investigate the voting methods by region. This would require Ballot ID information, sorted by type (mail-in ballots, punch cards, or DRE machines,) and then cross-referenced with the frequency of each type by region. This may uncover why turnout is lower in certain regions, and whether there are access barriers that need to be addressed.
