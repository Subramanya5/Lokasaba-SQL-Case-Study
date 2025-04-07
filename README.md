# Lokasaba-SQL-Case-Study
Lokasaba Preferences to the performance by each party in the lokasaba election of India

## SQL Case Study: Analyzing Indian General Elections (Lok Sabha)

### Overview
This repository contains a comprehensive SQL case study focused on analyzing data from Indian General Elections (Lok Sabha). The project includes multiple tables representing election-related information such as state-wise results, party performance, constituency details, and candidate statistics.

Using structured SQL queries, this case study aims to draw insights like the most successful political parties, vote margins, voter percentages, and candidate performance. The queries range from basic aggregations to complex subqueries and joins.

---

### Dataset Description

- **StateID**: Maps state codes (e.g., S01, S24) to their corresponding state names (e.g., Andhra Pradesh, Uttar Pradesh).
- **NoOfWins**: Lists political parties along with the number of seats won and a unique Party ID.
- **Constituency**: Contains information about each constituency, including the winning candidate, party, vote margin, and total votes.
- **CandidateDetails**: Stores all candidate details, such as party, EVM and postal votes, total votes, vote percentage, and constituency ID.
- **Results**: Captures election outcomes by linking constituency, leading/trailing candidates, vote margin, and state ID.

---

### Questions and Analysis

This case study explores the dataset through the following analytical questions:

1. Find the top 3 parties with the highest number of wins.
2. Find the total votes received by each party in all constituencies and display only those with more than 500,000 votes.
3. Find the candidates who received more than the average number of votes.
4. Find constituencies where the margin of victory is less than 5,000 votes.
5. Find the state with the highest number of constituencies.
6. Find the candidates who received the maximum percentage of votes in their constituency.
7. Find the percentage of candidates who received more than 50% votes in their constituency.
8. Find the total number of constituencies in each state where the margin is greater than 10,000 votes.
9. Find the party with the highest average votes per candidate.
10. Find all candidates and their winning status (LEFT JOIN with Constituency).
11. Find all constituencies and their respective parties.
12. Find candidates who contested and the details of their constituency.
13. Find total votes per state, ensuring all states are listed.
14. Generate all possible pairs of candidates from different parties.
15. Find the state with the highest number of constituencies won by a single party.

---

### Usage

Follow these steps to use this repository:

1. Clone this repository to your local machine.
2. Install a SQL database management system (e.g., MySQL, PostgreSQL).
3. Copy and execute the SQL script provided in `lokasaba_project.sql` to set up the schema and queries.
4. Analyze the results using the pre-written queries or write your own to derive further insights.

---

### Directory Structure

|-- data/ |-- state_id_mapping.csv |-- constituency_details.csv |-- candidate_details.csv |-- party_wins.csv |-- election_results.csv |-- lokasaba_project.sql |-- README.md

|-- data/ |-- state_id_mapping.csv |-- constituency_details.csv |-- candidate_details.csv |-- party_wins.csv |-- election_results.csv |-- lokasaba_project.sql |-- README.md
