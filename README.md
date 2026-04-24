# Election-Management-Project-DS# 

A console-based voting system built with *C, using **Singly Linked Lists* to manage candidates and voters dynamically.

##  Features
* *Add Candidates:* Dynamic node creation for candidate profiles.
* *Secure Voting:* Tracks Voter IDs in a separate list to prevent double-voting.
* *Live Results:* Tabular display of current standings.
* *Winner Detection:* Identifies the winner or current leader in case of a tie.
* *Memory Safe:* Full memory cleanup (free()) on exit.

##  Data Structures
* *Candidate List:* Stores ID, Name, Party, and Vote Count.
* *Voter Registry:* A linked list used to validate unique Voter IDs.

##  Quick Start
1. *Compile:* gcc election.c -o election
2. *Run:* ./election

##  Menu
1. Add Candidate
2. Cast Vote
3. Display Results
4. Find Winner
5. Exit
