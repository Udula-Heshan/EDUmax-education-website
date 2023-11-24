
To get Contact, Registration, Subscribe and Login details of the University, you should click the Login button and,
Enter,  Username = admin
	Password = pass


And you should create these 3 tables and database.(We used - MYSQL : WAMPP SERVER)

/*==================================*/
CREATE DATABASE University;
USE University;



/*====================================
        SUBSCRIBE TABLE
====================================*/
CREATE TABLE subscribe(
email	VARCHAR(50)	PRIMARY KEY
);


/*====================================
        REGISTRATION TABLE
====================================*/
CREATE TABLE registration(
name	VARCHAR(50),
email	VARCHAR(50)	PRIMARY KEY,
phone	VARCHAR(10)
);


/*====================================
        CONTACT TABLE
====================================*/
CREATE TABLE contact(
name	VARCHAR(50),
id	VARCHAR(13)	PRIMARY KEY,
email	VARCHAR(50),
message	VARCHAR(1000)
);

