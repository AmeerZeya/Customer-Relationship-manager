# Customer-Relationship-Manager
Web app to manage the customers first name , last name and email address developed using Java , Spring framework , HTML and CSS.

Users can do add , update and delete customers in the Web app .

# Local Installation
  1. Download the zip or clone the repository to a folder.
  2. Import the folder to Eclipse ( or your preferred IDE )
  3. create database and table via below mentioned sql script ( project DB dialect mySql )
  4. download and install Tomcat server 
  5. run the application on the server via the IDE


#Sql-script 
<pre>
*CREATE DATABASE  IF NOT EXISTS `web_customer_tracker` 
USE `web_customer_tracker`;
 
*DROP TABLE IF EXISTS `customer`;*

*CREATE TABLE `customer` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(45) DEFAULT NULL,
  `last_name` varchar(45) DEFAULT NULL,
  `email` varchar(45) DEFAULT NULL,
  PRIMARY KEY (`id`)
) 

INSERT INTO `customer` VALUES 
	(1,'Abhisheak','Roy','abhiroy@yahoo.com'),
	(2,'Aditya Mohan','Jha','jadityamohanjha@yahoo.in'),
	(3,'Ameer','Zeya','ameerzeya@yahoo.in'),
	(4,'Jatin','Nijawan','jatinNijhawan@gmail.com'),
	(5,'Shewtank','Mishra','shwetankmishra@gamil.com');*

</pre>

# Display

The web shows the list of customers currently present in the database

![image](https://user-images.githubusercontent.com/82048817/167897262-d63aeaa6-e0d4-44a3-ba73-4330c3cc28f2.png)


# Usage

All the web app operations as follows

## Create
User can create an entity with first name , last name and email address

![image](https://user-images.githubusercontent.com/82048817/167896007-d9e6de0e-4131-4206-9c6d-923e032d4e20.png)

## Update
User can update the entity details present in the DB

-click in update button
![image](https://user-images.githubusercontent.com/82048817/167897592-2cb54896-9896-4c4b-902b-2cc0e95e495c.png)

-update the customer details
![image](https://user-images.githubusercontent.com/82048817/167898578-83d1d82a-1dff-4148-915c-b2385fa84712.png)

-Save
![image](https://user-images.githubusercontent.com/82048817/167898812-42b70032-f8fc-4ed5-b7fa-606aaca276ab.png)


