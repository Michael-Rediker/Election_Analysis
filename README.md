# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each cadidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election shows that:
- There were "369,711" votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The cadnidate results were:
  - Charles Casper Stockham recieved "23.0%" of the vote and "85,213" number of votes.
  - Diana DeGette received "73.8%" of the vote and "272,892" number of votes.
  - Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
- The winner of the election was:
  - Diana DeGette, who received "73.8%" of the vote and "272,892" number of votes.
  
## Election Audit Summary
This script could be transferred to any election. The first would be by changing which election results are being accessed. At the beginning of our code we referenced to the CSV doc with these election results. In order to use it for other elections, we would need to dchange the csv doc being activated to the other election results. While I struggled to get together the county turnout results. The same logic can be used to determine voter turnout by city, state, or politcal party if that information is available in the other elections CSV file.
