# **Election Analysis**

## *Overview of Election Audit*

Our task is to create a vote count report to certify a congressional election in Colorado. Election results were provided as data in CSV format, consisting of a number for the ballot ID and a name for the county and candidate, respectively. Python was used to write algorithms that will assist the confirmation and analysis of election results.

## Results

	-369,711 total votes were cast in this congressional election
	-County breakdown:
		Jefferson: 10.5% (38,855)
		Denver: 82.8% (306,055)
		Arapahoe: 6.7% (24,801)
		*Denver had the largest number of votes (306,055)*
		
	-Diana DeGette won the election with 272,892 votes, 73% percentage of the total
		Charles Casper Stockham: 23.0% (85,213)
		Diana DeGette: 73.8% (272,892)
		Raymon Anthony Doane: 3.1% (11,606)

## Summary 

	With the Python script prepared, we can quickly tabulate winners and break down data by county.
	With city or party affiliation data, we could modify the script to report it. For example, we could create a dictionary to hold the city as the key and the votes cast in each city as the values. With a for loop, we could retrieve the city name from each row, then use a decision statement with a logical operator to compile a city breakdown.