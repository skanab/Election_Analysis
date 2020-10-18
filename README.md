# Election Analysis

## Overview of Election Audit
The election commission has requested an audit of the votes from a single congressional precinct in Colorado using python. The commission has provided the data in the election_results.csv stored in the [Resource folder](https://github.com/skanab/Election_Analysis/blob/main/Resources/) of this project. The data consists of CSV(comma separated values) of ballot ID, county, and candidate vote for each of the 369,711 votes contained in the file.

The commission has asked for the following:

* Total number of votes cast
* A complete list of candidates who received votes
* Total number of votes each candidate received
* Percentage of votes each candidate won
* The winner of the election based on popular vote
* The total number of votes each county received
* Percentage of votes each county received
* The county that had the highest turnout

## Election Audit Results
* How many votes were cast in this congressional election?

    `Total Votes: 369,711`
* Provide a breakdown of the number of votes and the percentage of each county's total vote.
    ```
    Jefferson: 10.5% (38,855)
    Denver: 82.8% (306,055)
    Arapahoe: 6.7% (24,801)
    ```
* Which county had the largest number of votes?

    `Denver`
* Provide a breakdown of the number of votes and the percentage of the total vote for each candidate received.
    ```
    Charles Casper Stockham: 23.0% (85,213)
    Diana DeGette: 73.8% (272,892)
    Raymon Anthony Doane: 3.1% (11,606)
    ``` 
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

    ```
    Winner: Diana DeGette
    Winning Vote Count: 272,892
    Winning Percentage: 73.8%
    ```

The below screen shot show the output of the python code. I have also included the results in file election_analysis.txt located in the [Analysis folder](https://github.com/skanab/Election_Analysis/blob/main/Analysis/) of this project.

![Election Results](https://raw.githubusercontent.com/skanab/Election_Analysis/main/Analysis/election_analysis.png)

## Election Audit Summary
While the provided python code was able to meet the Colorado election commission's immediate expectations for an audit of a single congressional district, I could expand it to allow the commission to audit other statewide elections. I propose the following changes.

1) Expand the data structure to include a congressional district identifier to allow for the auditing of congressional offices statewide.
2) Expand the data structures to include an office identifier to audit other state offices like the Governor, Attorney General, and Superintendent of Schools.

 Consolidating all elections audits onto a single platform would allow the election commission to save money and increase their efficiency during election cycles.
