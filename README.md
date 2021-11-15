# Election_Analysis

## Overview
The Colorado Board of Elections has tasked us with performing an audit of a recent local confressional election. The goals of this audit were to determine:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes, and the counties where those votes were cast.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. The voter turnout in each coounty
7. Calculate the percentage of votes for each county of the total votes. 
8. Determine the county with the highest voter turnout. 

## Resources
- Data Source: election_results.cvs
- Software: Python 3.10.0 , Visual Studio Code, 1.62.0
- Python Files: PyPoll_Challenge_starter_code.py

## Election Audit Results
The results of our election audit for the Colorado Board of Elections reveal that:

- There were a total of 369,711 votes cast in the election.

- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane

- The candidate results were:
  - Charles Casper Stockham received 23.0% of the total, with 85,213 votes.
  - Diana DeGette received **73.8%** of the total, with **272,892 votes**.
  - Raymon Anthony Doane received 3.1% of the total, with 11,606 votes.

- **The winner of the election was:**
  - Diana DeGette, who received 73.8% of the total votes, with 272,892 votes cast in her favor.

## County Results
- Jefferson County had a total of 38,885 votes cast, which accounted for 10.5% of the all votes.
- Denver County had a total of 306,055 votes cast, which accounted for 82.8% of the all votes. 
- Arapahoe County had a total of 24,801 votes cast, which accounted for 6.7% of the all votes. 

**Denver County had the largest voter turnout by almost 8x more than Jefferson County and almost 12x more than Arapahoe County.**

*see the results below:*

![election_results_terminal_Screenshot](https://github.com/Jflux05/Election_Analysis/blob/7304598d4763bec3c824ef5e8db81b120a4c78aa/Resources/election%20result%20screenshot%20terminal.png)
![election_results .txtfile screenshot](https://github.com/Jflux05/Election_Analysis/blob/7304598d4763bec3c824ef5e8db81b120a4c78aa/Resources/election_analysis.txtscreenshot.png)

## Election Audit Summary
The election audit was able to answer all of the election commission's questions that were laid out at the begining of the project. The commission now has the basis for a code that could be utilized to handle future elections. In its current state, the code is limited to this specific local election, however with a few tweaks to the script, it could process an output for any type of voter related data thats available (ie. average voter age or voter sex). While that may seem dynamic, we could make the code even more dynamic by utilizing the input() function in two ways:

   - In line 9 prompting the user to input a file name they plan to use (so the code can be applied to any file and not just the election_results.csv file).
   - In lines 49 and 52 prompting the user to input the column number where the desired metric is (as it can vary between files).
      
By making these small tweaks to the code, it could be utilized by the commission for future elections and if they choose to start collecting additional data points, it could easily process results that would give the commision further insights into the state's voters. 

