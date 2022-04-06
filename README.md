# Election_Analysis

## Project Overview

I was given the following tasks in order to complete an election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
3. Determine which county had the largest number of votes.
4. Get a complete list of candidates who received votes.
5. Calculate the total number of votes each candidate received.
6. Calculate the percentage of votes each candidate won.
7. Determine the winner of the election based on popular vote.

## Resources

- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code

## Results

The analysis of the election shows that:

There were 369,711 total votes cast in the election.

The number of votes, and percentage of votes for each county were:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
  
Denver county recieved the largest number of votes.

The candidates that received votes in the election were:
  - Charles Casper Stockham 
  - Diana Degette
  - Raymon Anthony Doane
  
The candidates recieved the following total votes and percentage of the total votes:
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)

The Winner of the election was Diana Degette.

## Summary

The script written for this analysis (PyPoll_Challenge.py) can be repurposed for any election. The script provides quick concise results for an election with the only input being a csv file containing all the votes cast in the election. If this script were to be repurposed for future elections the only thing that needs to be changed is the data file being read and its path, and the text file to write the results too. Additionally, much of the code in this script can be copied and edited to be used to calculate many other metrics of an election, like demographics, political party, etc. These metrics would simply need to be provided in the csv data file.


