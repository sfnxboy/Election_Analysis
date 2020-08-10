# Election_Analysis

## Overview of Election Audit
The Colorado Board of Elections defined the following list of tasks that must be completed for the election audit.
The information provided by the Board must then be communicated concisely.

•	Determine the total number of votes cast
•	Compile a complete list of candidates who received votes
•	Find the total number of votes each candidate received
•	Calculate the percentage of votes each candidate won
•	Determine winner of the election based on popular vote

## Resources
•	Data Source: election_results.csv
•	Software: Python 3.6.1, Microsoft Visual Studio 2019

## Election Audit Results
There was a total of 369,711 votes cast this election.
There were three candidates:
1.	Charles Casper Stockham
2.	Diana DeGette
3.	Raymon Anthony Doane
The candidate results were as follows:
•	Charles Casper Stockham received 23.0% of the vote, and 85,213 votes.
•	Diana DeGette received 73.8% of the vote, and 272,892 votes.
•	Raymon Anthony Doane received 3.1% of the votes, and 11,606 votes.
There was a total of three counties:
1.	Jefferson County
2.	Denver County
3.	Arapahoe County
The analysis of county-turnout is as follows:
•	10.5% of total turnout represented Jefferson County (38,855 voters)
•	82.8% of total turnout represented Denver County (306,055 voters)
•	6.7% of the total turnout represented Arapahoe County (11,606 voters)
The winner was Diana DeGette, who received 73.8% of the vote, and 272,892 votes.
Denver county saw the greatest voter turnout, representing 82.8% of the total vote, translating to a total of 306,055 voters.

## Election-Audit Summary
To the Colorado Board of Elections, this script may be recycled if the .csv files remain formatted as it is currently. To make this script more versatile, it would have to account for a change in the structure of the csv format. To be specific, the script relies on the county being in the second column of any row of the .csv file, and the candidate voted for to be on the third. The script can be modified to have the compiler itself identify the column which represents the county, and the column which stores the name of the candidate voted for. Furthermore, it can be modified to consider any electoral system set in place, and communicate any meaningful results found through a relevant analysis. This modification can be accounted for with a dictionary including each district and its respective number of points.

## Concluding Statement
Often, we must deal with massive amounts of data sets, and thankfully for computers we can automate the task of sorting the data. Data scientists often must wire together several applications to communicate a meaningful analysis, as seen in this project. This project was simple, I had to use one external .csv module containing data to parse, and another .txt to communicate the data. Using basic programing techniques such arrays and dictionaries to store parsed data, and conditionals and iterables to store the data, we communicated a relevant statistic.
