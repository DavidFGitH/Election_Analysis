# Election_Analysis
Performing Election Analysis with Python

## Overview of Project

To automate and analyze election audit data using Python 

### Purpose

The purpose of the project was to perform an election audit by taking the data of the election provided and creating a Python program that would run through the data and provide various data analytics and results.

## Election-Audit Results

- A total of 369,711 votes were cast in this election.

- Jefferson county had 38,855 votes which accounted for 10.5% of the votes. Denver county had 306,055 votes which accounted for 82.8% of the vote. Finally Arapahoe county had 24,801 votes with 6.7% of the votes.

- Using the results provided, Denver had the largest number votes with a vast majority (82.8%) of the votes in the election.

- Among the candidates, Charles Casper Stockham had 85,213 votes accounting for 23.0% of the total vote, Diana DeGette had 272,892 votes accounting for 73.8% of the total vote and Raymon Anthony Doane had 11,606 votes accounting for 3.1% of the total vote.

- Looking at the results, it is clear Diana DeGette won the election with 272,892 votes, which was about 73.8% of the total vote.

## Election-Audit Summary

At it's current state, the code provides an automated method to go through all the votes in a csv file and as long as the data is organized and formatted to the structure that the program was designed for, the code will go through the election data and automatically find all the candidates and counties without prompts and provide a count for all counties and candidates as well as the percentage of the votes and a quick output on who won the election and which county had the largest turnout. In order to adapt the code for other elections, we could modify the code to account for additional factors, such as party affiliation and city or location where the ballot was cast. Increasing the number of variables the code could account for could be very helpful in doing election audit analysis and giving more context inside the data. Another modification we could do to the program would be to combine slices of data together, for example, if we tried to combine the number of votes Diana DeGette received with which counties had the most votes for Diana DeGette. Since the goal of the program is to aid in the election audit process, being able combine factors would help in illuminating the data as well. Finally, modifying the program to address disparities would help in adapting the program to elections as well. Aggregating all the votes to different factors and making sure they all sum to the total votes would help a lot in an election audit.