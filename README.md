# SimpleDB 
This simpleDatabaseSystem which is known as SimpleDB that was originally wirtten by Rex Ren and his colleage at UC Berekley's Database 
class CS186. [The original repository](https://github.com/rexshihaoren/SimpleDB)

This repository consists of an edited version of the original system which has designed for multiple programming assignment in order to 
familiarize the trainees with the fundumental of Database Systems and their low level implementations. 
It gives the oppurtunity for one to have an appreciation of the complex computations the known systems such as Oracle and SQL Server goes 
through such as buffering, joining, paging and etc. 

### Extracted from the original repository the archtecure of system breaks down into 6 main category: 
1. Classes that represent fields, tuples, and tuple schemas;
2. Classes that apply predicates and conditions to tuples;
3. One or more access methods (e.g., heap files) that store relations on disk and provide a way to iterate through tuples of those relations;
4. A collection of operator classes (e.g., select, join, insert, delete, etc.) that process tuples;
5. A buffer pool that caches active tuples and pages in memory and handles concurrency control and transactions (neither of which you need to worry about for this project); and,
6. A catalog that stores information about available tables and their schemas.

The system has been written in Java and contains multiple Junit test for each assignment (Unit and System testing). 

The main purpose of repository is to show an attempt for solving some of the assignment questions. 
