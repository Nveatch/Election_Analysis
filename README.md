# Python Election Analysis
	
## Overview of Project

### Purpose
The purpose of this election analysis was to take a .csv file full of voter data and determine the following:
1. The Total Votes Cast
2. Which counties those votes came from, and how they were distributed
3. The county which had the highest voter turnout
4. Who the votes were cast for, and how they were distributed per candidate
5. The winner of the election and the number of votes they received (as well as that percentage of votes out of the total)

## Results
![Results](https://github.com/Nveatch/Election_Analysis/blob/main/Resources/Results.png)

-**How many votes were cast in this congressional election?** 369,711 Votes

-**Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**
![County Vote Breakdown](https://github.com/Nveatch/Election_Analysis/blob/main/Resources/County_Votes.png)

-**Which county had the largest number of votes?** Denver

-**Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**
![Candidate Vote Results](https://github.com/Nveatch/Election_Analysis/blob/main/Resources/Results.png)

-**Which candidate won the election, what was their vote count, and what was their percentage of the total votes?** Diana DeGette won the election with 272,892 votes (73.8% of total votes)

## Election Audit Summary
This application is very flexible, and could be applied to other elections in other counties, as both the lists for candidate options and counties update themselves, and so will autofill with whatever information being fed in via CSV. Therefore, if you wanted to use this script for other elections, you could:

-Change the data in the second column of the "election_results" CSV file to whatever counties you wanted to use the script for. It would then pull those new counties (and by association, new candidates) into the script and display the results accordingly.

-Scale this script up for a state level election. Depending how those votes were organized, you could keep the "county" nomenclature in the script, or change it to perhaps "cities", "districts", etc. 