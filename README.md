# Election_Analysis

## Overview of Election Audit
Tom and his manager, Seth, are both members of the Colorado Board of Elections and they are responsible for completing an election audit of a recent local congressional election. Votes were received using three different methods: Mail-In Ballots, Punch Cards and Direct Recording Electronic (DRE) counting machines. Our task is to automate the reporting process and output the following details:

    1.	The total number of votes cast.
    2.	A complete list of candidates who received votes.
    3.	The number of votes each candidate received.
    4.	The percentage of votes each candidate won.
    5.	The winner of the election based on the popular vote.
    
## Results
To meet our deliverables, Python and Visual Studio Code were used to reference the election results CSV file that we received from Tom. Using lists, dictionaries, conditionals, and loops, we were able to generate the following results:

![Election_Results](/election_results.PNG)

This analysis shows that:
    
    1. 369,711 votes were cast in this election.
    2. The candidates were Charles Casper Stockham, Diana DeGette and Raymon Anthony Doane.
    3. Charles received 85,213 votes, Diana received 272,892 votes, and Raymon 11,606 votes.
    4. Charles won 23.0% of the votes, Diana won 73.8% of the votes and Raymon won 3.1% of the votes.
    5. Diana DeGette won the election based on the popular vote.

In addition to generating the requested deliverables, we were also able to output the number and percentage of votes from each county and determine that Denver had the largest voter turnout. 

## Summary
Now that we have automated the reporting process, we can apply the same script we used for this election in future elections. While this script meets and exceeds Tom and Seth’s expectations, improvements can still be made.  For example, code could be written to loop through the ballot IDs to ensure that there are no duplicates due to human error. We could also gain more insight from the election results data to show the percentage of eligible voters in each county who actually cast their ballot. 
