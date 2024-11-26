# SQL-Project---INDIA-GENERAL-ELECTIONS-RESULT-ANALYSIS-2024

**Project Description:**
The India General Elections Result Analysis 2024 project aims to provide detailed insights into the election results using SQL and SSMS. By analysing the results at the state and constituency levels, the project offers comprehensive insights into seat allocation, voting patterns, and party performance. It involves querying, transforming, and analysing election data stored in relational databases to answer critical questions related to alliances, winning margins, and voting methods.
The primary objective is to empower stakeholders, including political analysts, policymakers, and citizens, with data-driven insights into the electoral outcomes of 2024.

**Project Teckstack:**
1. SQL
2. ToolS: SQL Server Management Studio (SSMS)

**Features:**
1.	Total Seat Analysis:
  a.	Queries determine the total number of seats available for elections at the national and state levels.
2.	Party and Alliance Performance:
  a.	Identification of seats won by NDA, I.N.D.I.A, and OTHER alliances.
  b.	Breakdown of party-wise seats won under each alliance.
3.	Winning Candidate Insights:
  a.	Fetches the names, party affiliations, total votes, and victory margins of winning candidates at the state and constituency levels.
4.	Vote Distribution:
  a.	Analyses the distribution of EVM votes versus postal votes for specific constituencies.
5.	State-Wise Party Analysis:
  a.	Identifies which parties won the most seats in each state and provides a detailed count.
6.	Candidate Rankings:
  a.	Lists the candidates with the highest EVM votes across all constituencies, ranking the top 10.
7.	State-Specific Breakdown:
  a.	For Maharashtra, calculates the total seats, candidates, parties, and total votes with a breakdown of EVM and postal votes.
8.	Alliance Comparisons:
  a.	Determines which alliance won the most seats nationally and provides state-wise breakdowns.
9.	Custom Column Addition:
  a.	Adds a new column in the database to classify party alliances dynamically as NDA, I.N.D.I.A, or OTHER.

**Problem Statement:**
1.	Total Seats
2.	What is the total number of seats available for elections in each state
3.	Total Seats Won by NDA Allianz
4.	Seats Won by NDA Allianz Parties
5.	Total Seats Won by I.N.D.I.A. Allianz
6.	Seats Won by I.N.D.I.A. Allianz Parties
7.	Add new column field in table partywise_results to get the Party Allianz as NDA, I.N.D.I.A 
and OTHER
8.	Which party alliance (NDA, I.N.D.I.A, or OTHER) won the most seats across all states?
9.	Winning candidate's name, their party name, total votes, and the margin of victory for a specific state and constituency?
10.	What is the distribution of EVM votes versus postal votes for candidates in a specific constituency?
11.	Which parties won the most seats in s State, and how many seats did each party win?
12.	What is the total number of seats won by each party alliance (NDA, I.N.D.I.A, and OTHER) in each state for the India Elections 2024
13.	Which candidate received the highest number of EVM votes in each constituency (Top 10)?
14.	Which candidate won and which candidate was the runner-up in each constituency of State for the 2024 elections?
15.	For the state of Maharashtra, what are the total number of seats, total number of candidates, total number of parties, total votes (including EVM and postal), and the breakdown of EVM and postal votes?

**ER Diagram:**
![image](https://github.com/user-attachments/assets/5ecf706b-eeab-407f-8849-f8de5697ea3a)

**Conclusion:**
The India General Elections Result Analysis 2024 project demonstrates the power of SQL and SSMS for data analysis. By leveraging complex queries and data transformations, the project provides valuable insights into election trends and outcomes. It helps identify winning strategies, voting behaviours, and alliance performances, enabling stakeholders to better understand the dynamics of the electoral process. The project’s structured approach and rich analysis establish a scalable framework for future election data analysis.
