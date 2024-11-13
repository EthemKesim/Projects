USA Voting System 2024

Overview
This is a basic voting system we built to practice core programming skills in Python, C#, and JavaScript. It allows users to cast ballots for candidates in a mock election, showing how the same functionality can be implemented across languages.

Purpose
The goal was to create an easy-to-use application for conducting elections on a small scale. We wanted to demonstrate constructing a simple voting mechanism with candidate registration and tie-breaking capabilities.


Features
Name Check: Users provide their name to verify identity before voting
Candidate Options: Preset list of choices displayed for selection
Tallying Votes: Ballots are totaled after each round and results are printed.
Results Summary: Visual summary of vote percentages at the end.


Technologies
Python: Command-line interface using basic input/output

C#: .NET console app with System.Console for I/O

JavaScript: Node.js app with readline module for console I/O


Usage Guide
To run each version:

Python: Navigate to folder, run python voting_app.py

C#: Navigate to folder, run dotnet run

Node.js: Navigate to folder, run node voting_app.js


Interface Walkthrough
The interface guides users through candidate registration, voting and results display. Prompts and validation ensure a smooth experience.

Voting Process
1.	Users enter their name and surname to verify their identity.
2.	Candidates are displayed with corresponding numbers.
3.	Users vote by selecting the candidate's number.

Tie-Breaking Round
If there's a tie, a new round is started with only the tied candidates. The process continues until a winner is determined.

Project Structure
The project is organized by language, with each version containing its own main program file.

usa-voting-system-2024/

1.python_version/
  1.1voting_system.py
  
 2.csharp_version/
  2.1Program.cs/
   2.2VotingSystem.csproj

 3.javascript_version/
   3.1voting_system.js

README.md

________________________________________
Enhancements
Future iterations could include:

Database for storing votes
Web-based interface
Additional voting features like write-ins
________________________________________
Conclusion
This project let us apply core programming principles while comparing implementations across languages. The simple voting application can serve as a starting point for more robust election systems.
________________________________________

