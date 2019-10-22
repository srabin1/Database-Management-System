# Database-Management-System
*** All commands are for windows user, you also can find a command for Linux or Mac users simply.***
Assignment#1:
This is the first Excercise in database management system course.
The task is run a test1.java file in a command prompt or terminal and see the result.
1. Download Java JDK at http://www.oracle.com/technetwork/java/javase/downloads/index.html (Links to an external site.)
2. Make sure you have the global java running environment by typing java under any folder in the terminal
Configure your Windows 10 environment by checking the web: https://www.mkyong.com/java/how-to-set-java_home-on-windows-10/ (Links to an external site.)
3. Download the two files from the link at the bottom: test1.java and the mysql-connector-java-5.1.32-bin.jar
4. Compile the test1.java by using the command: java -cp .\mysql-connector-java-5.1.32-bin.jar test1.java
To successfully run the commands above, you need to connect with the school network (WSU WIFI), or to use a machine on campus that connects to the same network (in any classroom that has computers)!
_________________________________________________________________________________________________________________________________________
Assignment#2:
This is the second Excercise in database management system course.
The task is create a new database chema by a local user in Mysql workbench and run a test2.java file in a command prompt or terminal and see the result.
1. Download MySQL Server on https://dev.mysql.com/downloads/windows/
2. Download test2.java (found at the bottom of this message)
3. Download the latest version of the MySQL JDBC connector https://mvnrepository.com/artifact/mysql/mysql-connector-java
4. Create a local user "john" with the password "pass1234" on MySQL Workbench and open it, run the following code:
CREATE DATABASE testdb;
USE testdb;
CREATE TABLE people (
     name varchar(50),
     email varchar(50),
     country varchar(50)
);

INSERT INTO people VALUES ('John Smith','shiyonglu@gmail.com', 'USA');
INSERT INTO people VALUES ('Kathy Brown','kathy@gmail.com', 'USA');
INSERT INTO people VALUES ('Newton Franklin','newton@gmail.com', 'Turkey');

SELECT * from people;
4. Compile and run test2.java with the following command. Notice you may need to change the name regarding the version you are using for the jar file: java  -cp .\mysql-connector-java-8.0.17.jar test2.java

_______________________________________________________________________________________________________________________________________
Assignment#3:



