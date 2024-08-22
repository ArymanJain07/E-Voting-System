## E-Voting System with ASP.NET MVC

It is an E-Voting system made in the Asp.NET MVC project. Information such as voter, candidate, vote, e-mail, password are stored in the database.

### Methodology:
The system is built on a web based Asp.NET MVC project. Voter information, candidate information, vote, election results is kept in a relational database. The votes used is recorded in the database with the RSA encryption algorithm. General operation is as follows, voters access a panel where they can vote after logging into the system with their username and password. Candidate information is listed on the panel and the voter uses the vote. After the voting is over, the votes cast are counted and the results are displayed graphically in the system.

###	Interface:
A website that has both an interface for voters and a management panel is developed. A system is established where voters can vote, view results of votes, and view candidate information. Design part is established with HTML, CSS, JS and Bootstrap libraries. It is in C # programming language. ASP.NET Core project and MVC framework is used.

### Dataset:
Microsoft SQL Server Management Studio 2020 is used as the database system. Entity Framework will be used for operations such as CRUD transactions on the system. Adding data will be done with JQuery, which is a JS library.

###	Encryption Algorithms:
The passwords of the voters used in system login will be encrypted with Crypto Helpers and MD5 encryption function is used. RSA algorithm is used for encryption of votes. For this, the System.Security.Cryptography library is used. 
