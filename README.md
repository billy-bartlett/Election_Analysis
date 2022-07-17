# Election_Analysis

## Project Overview
### Overview of Election Audit
A Colorado Board of Elections employee asked me to perform analysis for an audit of a recent local congressional election. I was asked to deliver the following:
1. The total votes cast in the congressional election.
2. A breakdown of the number of votes and the percentage of total votes for each county in the precinct.
3. The county with the largest number of votes.
4. A breakdown of the number of votes and the percentage of the total votes each candidate received.
5. Which candidate won the election, their vote count, and their percentage of the total votes.

## Election-Audit Results
**The analysis of the election shows that there were 367,711 votes cast in the election.**
### County Results
The turnout for each county was as follows: 
- Jefferson County had 10.5% of the votes with 38,855 total votes. 
- Denver County had 82.8% of the votes with 306,055 total votes. 
- Arapahoe County had 6.7% of the votes with 24,801 total votes. 

**The county with the highest turnout was Denver County, which had 82.8% of the votes with 306,055 total votes.** 

### Voting Results
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the votes and 85,213 total votes.
    - Diana DeGette received 73.8% of the votes and 272,892 total votes.
    - Raymon Anthony Doane received 3.1% of the votes and 11,606 total votes.

**The winner of the election was Diana DeGette, who received 73.8% of the votes and 272,892 total votes.**

![Election_Results](https://user-images.githubusercontent.com/101153516/179382528-cbc5e66f-db4f-43c9-a468-3508506920fd.jpg)

## Election-Audit Summary
This code can easily be utilized for future elections with small edits to the existing code. By updating the data source of this code, you can analyze future election results very quickly. All you need to do is update the csv file path as shown below.

![Data_Source](https://user-images.githubusercontent.com/101153516/179382891-8186ee48-6c8a-4fbc-8ad0-36c3ddd072fb.jpg)

You also have the ability to edit where the data is saved. You can elect, pun intended, where you want data to live. Whether you want to keep all the results in the same document, or want to save certain data points in other locations, you have the freedom to decide where data is stored by updating the "file_to_save" path as shown below. 

![File_to_Write](https://user-images.githubusercontent.com/101153516/179382950-7bacd8d3-e5ea-4da7-9773-b5e1ce025182.jpg)

This code can also be refactored to analyze data sources that include additional data points. Should you ever want more visibility into election data, the code can be altered to meet your needs. A few examples of additional data points are time of voting, age of voter, and where the vote was cast. 

## Resources
Data Source: election.results.csv
Software: Python V 3.9.12, VS Code V 1.69.1
