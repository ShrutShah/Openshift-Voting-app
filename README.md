# Openshift-Voting-app

https://medium.com/@sdhah1999/implementation-of-microservices-on-openshift-4-2-container-platform-fd2764da2d7

A Python webapp which lets you vote between two options (Flask).

A Redis queue which collects new votes (Redis Ephemeral).

A .NET worker which consumes votes and stores them in (Maven-Java-JAR).

A Postgres database backed by a Docker volume(PostgreSQL).

A Node.js webapp which shows the results of the voting in real time (Node.js).

Input UI
![image](https://github.com/ShrutShah/Openshift-Voting-app/assets/43044788/89251f5b-6419-4195-a4a3-760c21f06573)

Output UI
![image](https://github.com/ShrutShah/Openshift-Voting-app/assets/43044788/7c46ebb8-d32d-4aaf-805e-a4d41899fdae)

This Seamless flow can be accomplished with Openshift Container Platform.


