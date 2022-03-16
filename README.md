# Election_Analysis
# Analysis of Election results

# Overview of Election Audit
Assisted an election team to submit an election audit utilizing Python programming and CSV database to the election commission.
        The purpose of this election analysis is to complete an audit that will display:
        
        * The voter turnout for each county
        * The percentage of votes from each county out of the total count
        * The county with the highest turnout

# Election Audit Results
The election audit displayed the following results:
* Total votes cast: 369,711
* Counties:
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (306,055)
  * Arapahoe: 6.7% (24,801)
  
The largest voter turnout was Denver which had 82.8% (306,055) voters.

The candidate results were:
* Charles Casper Stockham had 23.0% of the votes with 85,213 votes.
* Diana Degette had 73.8% of the votes with 272,892 votes.
* Raymon Anthony Doane had 3.1% of the votes with 11,606 votes.

The candidate who was the winner was Diana DeGette with 73.8% (272,892) votes cast.


# Election Audit Summary
The election script that was created can be modified for any future election campaigns to show voter turnouts, votes that were casts, and can 
be easily modified to for unlimited election results. 

* A list that will show voter age can be created with a list and dictionary age(), age_votes[]
* Extract age from the database age_name = row[x]
* Count the number of votes by age_votes

Another example can be created with user input by year.
* print("What year do you want?"), Year = ("2019","2020","2021")


