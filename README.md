
## Configuration
In this project, you’ll find 2 files with the configuration we used: 
-	pom.xml with dependencies HADOOP and HBase needed to build the jar
-	manifest.mf with the class-path of all jar needed to use the jar 

## Database of social network project
This program simulate a simple social network database: each person has a unique lastname, informations about him, a list of friends and one best friend. 
The program permits to display, add and remove people informations, best friend and friends and create or delete a person.

## Problems with jar
Unfortunately, a problem occurs with the jar: we can’t launch it on the cluster, but it’s still available in the out directory.
