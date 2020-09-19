Team Members: MEGHA VIJENDRA(1001736938)
	      ARPITHA VENKANNA PATIL(1001777613)

Database Used: Database design using MYSQL Workbench. 

Database program : Java with JDBC(Using Eclipse IDE).
	           The Java program imports the necessary classes for the execution of the JAVA file which is connecting to
		   the MYSQL.
                   We have also imported the csv files(country, players, player_assists_goals, players_cards, match_results)
                   in the Eclipse IDE and placed in a seperate folder for easier access then executed.

Zipped Directory: Project1_First_Phase include these files: 
			1)DataHandler.java
			2)create and insert spool(create, table_view)
			3)readme.txt
			4)CREATE SQL.sql

NOTE:
1.Since we are using Eclipse IDE to insert the values into the created tables, we would be adding the JDBC
  connection dependency in the pom.xml as follows:
    <dependency>
    <groupId>mysql</groupId>
    <artifactId>mysql-connector-java</artifactId>
    <version>8.0.17</version>
    </dependency>

2.As we are loading the data into the tables using JAVA program, we need to change the value of the variable "table" to
  the table name to which we are going to load the table data into.

3.To make the connection using JDBC, we have used the grant permission commands.
   
3.While running the java code remember to change the pathname of the csv file.

4.Edit the insert query by changing the insert tablename for all 5 tables.


 		
