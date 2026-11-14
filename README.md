MIT 8103 Advanced Database Systems Portfolio
Case Study: Munchiba Hotel & Suites Reservation System
Academic Session: 2026/2027
Database Technologies: PostgreSQL and MongoDB

About This Repository
This repository consists of SQL script files, MongoDB commands, results from experiments, screenshots, and documentation that I created for the portfolio assessment for the course MIT 8103 – Advanced Database Systems.
For all the five practical exercises, I have taken an imaginary hotel, Munchiba Hotel & Suites.

Repository Structure

Portfolio
Folder
Main Activities
1 – Database Design and Modelling
portfolio-1-database-design
Relational schema, ERD, tables, keys and constraints
2 – Query Processing and Optimisation
portfolio-2-query-optimisation
SQL queries, execution plans and indexing
3 – Transactions and Concurrency
portfolio-3-transactions-concurrency
COMMIT, ROLLBACK, isolation and locking
4 – NoSQL and Advanced Data Models
portfolio-4-nosql-advanced-data-models
MongoDB documents, queries and updates
5 – Distributed and Cloud Database
portfolio-5-distributed-cloud-database
Replication, failover and node recovery


In each folder is its own README file which provides more information on the practical exercise.

Software and Tools

Tools
Purpose
PostgreSQL
Relational database implementation
pgAdmin 4
SQL execution and database administration
MongoDB Community Server 9.0
Document database and replica set experiments
MongoDB Compass
MongoDB connections, queries and data inspection
MongoDB Shell
Replica set administration and testing
GitHub
Version control and evidence documentation


How to Review My Portfolio

Portfolio 1 – Database Design
Open the Portfolio 1 folder to see the database design, SQL statements, relationship implementation screenshots, etc.
The relational database includes six tables: Guest, RoomType, Staff, Room, Reservation and Payment.

Portfolio 2 – Query Optimisation
Open the Portfolio 2 folder to see the SQL statements, index performance experiment, and compare the execution plans.
The experiment was carried out on the basis of performance of 10,000 test records.

Portfolio 3 – Transactions and Concurrency
Open the Portfolio 3 folder to see the experiment with transactions with the use of the following operations: COMMIT, ROLLBACK, constraint handling, concurrency handling, and locking.
The files include the used commands, observed results and corresponding screenshots.

Portfolio 4 – MongoDB NoSQL Implementation
Open the Portfolio 4 folder to see the exported JSON reservation documents and MongoDB query experiments. The MongoDB NoSQL database is implemented with a document-oriented approach to hotel reservation information storage.

Portfolio 5 – Distributed Database Experiment
Open the Portfolio 5 folder to review the MongoDB replica set experiment in your local environment.
The supporting files include:
`mongodb_replica_set_commands.js` - commands for configuring the replica set and testing it.
`mongodb_experiment_results.md` - Results of the experiment.
`screenshots/` - Screenshots of the practical part of the experiment.
`README.md` - Description of the implementation.

The experiment used three local MongoDB nodes:

Node
Address
Final State
Node 1
127.0.0.1:27018
SECONDARY
Node 2
127.0.0.1:27019
PRIMARY
Node 3
127.0.0.1:27020
SECONDARY


The test included primary failure, automatic election of a new primary, successful insertion after the failure, replication to a different secondary and recovering the failed node.
Note: The tests were performed on a local replica set simulation on one computer running Windows operating system. Sharding was considered but not done.

Running the Experiments
PostgreSQL experiments need PostgreSQL Server as well as any SQL Client like pgAdmin 4.
MongoDB experiments will need MongoDB Community Server and MongoDB Shell/Compass.
For reviewing/repeating the exercise:
1. Open the respective portfolio folder.
2. Read the README file within to get some background.
3. Go through the SQL/MongoDB scripts.
4. If required, follow the instructions step-by-step.
5. Verify the output by comparing with the provided screenshot/experiment notes.
Some scripts correspond to various stages of the same experiment and should not be run simultaneously without reading instructions. Specifically, creation of MongoDB replica set needs to be done when setting up a new replica set.

Evidence and Documentation
I have arranged the repository in such a manner that the practical work becomes traceable. The supporting files consist of database queries, query results, screenshots, exported data, and README files.
All guest and reservation records used for evaluation are fictional.
Project Summary
The contents of this repository serve as proof for my assessment in MIT 8103 Advanced Database Systems portfolio. The final documentation gives detailed information on the activities carried out and the lessons learned.

