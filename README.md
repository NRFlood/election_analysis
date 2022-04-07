# Election analysis using Python in VS Code

## Overview of Election Audit

The purpose of this project was to help Seth and Tom dig a little deeper into the election results to provide some greater insights into the performance of each county to accompany the data already provided for each candidate. To generate these insights we had to create some additional lines of Python code within an existing script to perform the appropriate calculations needed to analyze each county and determine where the largest voter turnout occurred  

## Election Audit Results

By adding the appropriate code to the script I was able to calculate the voter turnout, percentage of votes, and highest voter turnout for each county. To generate these calculations I leveraged the existing candidate summary portion of the script as a guide for creating the code needed to add the county summary to the script.  This proved to be very helpful as it made the process shorter since I did not have to generate very similar code from scratch, particularly in section 6 and 7 pictured below. 

![Code](https://github.com/NRFlood/election_analysis/blob/main/Code%20Example.png)

Upon running the code with the added county information I was able to conclude the following:

• *How many votes were cast in this congressional election?*   **369,711**

• *Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.*

      Jefferson : 10.5% (38,855)
  
      Denver: 82.8% (306,055)
  
      Arapahoe: 6.7% (24,801)


• *Which county had the largest number of votes?*   **Denver**

• *Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.*

      Charles Casper Stockham: 23.0% (85,213)

      Diana DeGette: 73.8% (272,892)

      Raymon Anthony Doane: 3.1% (11,606)

• *Which candidate won the election, what was their vote count, and what was their percentage of the total votes?* 

   **Diana DeGette won the election with 272,892 votes, which represented 73.8% of all votes that were cast.**

## Election-Audit Summary

I propose that the election commission leverage this script for any election and modify it as needed to include the proper elements of the election it is being applied to.  One modification may be to include the political party each candidate represents.  With that type of information available in the raw data, additional code could be added to the Python script that would provide further insight into the political leanings of each county based on the political affiliation of each candidate.  I also think the script could be easily modified to provide insight at possibly a higher state level or lower level city level, which would provide additional visibility into where certain candidates are having success or struggling to gain votes.
