**Election Analysis**

**Overview of Election Audit**

The purpose of this election audit analysis was to provide the results to the election commission.  While they wanted to know the winning candidate, we also had to code information for the county resutls.  I added for loops and if statements to determin the county vote outcomes and the largest county turnout.  

**Election-Audit Results**

- There were a total of 369,711 votes cast in this congressional election.

- Following is a list of the counties and their total votes and percentage of the total.
    - Jefferson county had 38,855 votes or 10.5% of the votes.
    - Denver county had 306,055 votes or 82.8% of the votes.
    - Araphahoe county had the lowest votes coming in at 24,801 or 6.7% of the votes.
    
As you can see from the list above, Denver county had 306,055 votes which was the county with the highest votes.

-  Following is a list of the candidates and their total votes and percentage of the total.
    - Charles Casper Stockham had 85,213 votes or 23.0% of the total votes.
    - Diana DeGetter had 272,892 votes or 73.8% of the total votes.
    - Raymon Anthony Doane had the lowest votes coming in at 11,606 or 3.1% of the total votes.
    
 As you can see from the list above, Diana DeGette won the election with 272,892 votes or 73.8% of the total votes.
 
 To get the totals for the county and the candidates, I setup a counter to gather the total votes.  In addition, I created a county and candidate list along with a dictionary for the county and candidate lists which you can see below.
 
total_votes = 0
-   Above is setting up the total votes counter.
   
candidate_options = []

candidate_votes = {}
-   Above is setting up the candidates list and the dictonary for the candidate votes.

county_list = []

county_votes = {}
-   Above is setting up the county list and the dictionary for the county votes.
 
 **Election-Audit Summary**
 
Going forward, this program can be used for future elections to gather total votes per county and candidates along with determining the winning candidate.  To use for antoher election, you would have to update lines 9 with the file name with the data and line 11 as the name of the file you want to write the results to.  I think it would be interesting to include the number of votes each candidate gets from each county.  To do this, you would have to great another for loop and retreive the county votes per each canddidate.  It would tell another part of the story and what county the candidates are getting the majority of their votes. from. 
 
 
    

