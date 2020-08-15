# Election Analysis
## Overview of Election
The purpose of this is to analyze the election between the three candidates Charles Casper Stockham, Diana DeGetter, and Raymon Anthony Doane. We were to able see how many total votes was casted, how many people voted from each county, how many votes were casted for each candidate, the vote percentage, and the overall winner of the election. 

## Election Results
The results of the election are of the following:

Total Votes:
- 369,711 votes

County Votes:
- Jefferson 10.5% (38,855 votes)
- Denver 82.8% (306,055 votes)
- Arapahoe 6.7% (24,801 votes)

Candidates:
- Charles Casper Stockham 23.0% (85,213 votes)
- Diana DeGetter 73.8% (272,892 votes)
- Raymon Anthony Doane 3.1% (11,606 votes)

Winner of Election:
- Candidate: Diana DeGette
- Winning Vote Count: 272,892 votes
- Winning Vote Percentage: 73.8%

## Election Summary
This code can be used for any election. Because I have set the lists and dictionaires to empty sets, if you had the same headers for the data, it will run. Some changes that would probably have to change is the file paths for the file to load and the file to save. Those are easy to change. For the file to load, all you would have to change is the folder name and the file name. For myself, I have decided to put the data in a folder called "Resources" and the file name is "election_results.csv". This would be the same with the file to save. 

```
file_to_load = os.path.join("Resources", "election_results.csv")
```
If the data had different headers, you would have to change the row in able to get the candidate's name and the county name. Again, easy fixes because I have set those lists and dictionaries to an empty set. 

```
# Get the candidate name from each row.
        candidate_name = row[2]

# 3: Extract the county name from each row.
        county_name = row[1]
 ```
