## Overview of Election Audit: Explain the purpose of this election audit analysis.
The overview of the election audit was to determine the total votes, county votes, largest county turnout, candidate votes/percentages, and the candidate winner.

##Election Outcomes Analysis
- ![image](https://user-images.githubusercontent.com/107594143/178264912-16197c6b-4910-45b6-8c6e-8d070a6286f2.png)
  These lines of code help create a 'unique' function similar to that in vba. The county_options/candidate_options create a separate 'bucket' and appending the existing county_names/candidate_names to the 'bucket' helps find unique values. The for loop skips the first header line and reads row[1] and row[2], respectively. 
- ![image](https://user-images.githubusercontent.com/107594143/178265972-e49affba-6b5f-4c87-8525-4bf689baad52.png)
  These lines of code set the appropriate variables, lists, dicts, and zero values for the code to work.
- ![image](https://user-images.githubusercontent.com/107594143/178266727-21920ebd-1589-4b43-855f-a041be2fa35e.png)
  This section prints election results line, total votes casted and importantly - prints 'County Votes' for the next segment. I tried placing ths line in the f string county_results and it printed three times with every county. 
- ![image](https://user-images.githubusercontent.com/107594143/178267141-c1725bea-0614-43b3-b111-8932a26ea32c.png)
   This section uses if statement to filter out the county with the most votes. The f string prints only prints the winning candidate; therefore showing only one.
- ![image](https://user-images.githubusercontent.com/107594143/178267950-5a205032-4182-497a-94ce-a2c944861cb7.png)
  Lastly, the candidates with their total votes and percentages are displayed. The winning_candidate_summary f string prints out only one candidate -  the winner in this case is Diana DeGette. 
#How many votes were cast in this congressional election?
According to the analysis, there were 369,711 votes casted.
#Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  -County Votes:
    -Jefferson: 10.5% (38,855)
    -Denver: 82.8% (306,055)
    -Arapahoe: 6.7% (24,801)
#Which county had the largest number of votes?
  - Largest county with most votes is Denver.
#Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Candidate total votes and percentages:
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)
#Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
- The winning candidate was Diana DeGette wtih 272,892 votes and a winning percentage of 73.8%.

#Election - Audit Summary
- This script can be used to determine with accuracy and efficiency the total votes casted, percentages of votes, candidate winners, and voter turnouts per area. This script can be modified in two ways. The first way is to isolate for each county and find out the breakdown of votes per candidate. Lastly, the code can be modified to isolate for each candidate and find out the breakdown of votes for each county.
    
