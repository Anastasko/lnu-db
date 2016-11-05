to get xml from db run

0) remove output.xml  
1) cd liquibase  
2) ./liquibase --changeLogFile="../output.xml" generateChangeLog  

to update schema

0) cd liquibase  
1) ./liquibase --changeLogFile="../output.xml" update



