Design a mysql database. Requirements are as follows

We have a user entity with columns username, password
Every use can have multiple addresses. Address entity will have column street, pincode, country, state, phone no. So one user can have multiple addresses.
Design a db structure for this using create table sql syntax

CREATE TABLE User(
Username varchar (200),
Password varchar (200)
);

CREATE TABLE Address (
Street varchar (100),
Pincode varchar (6),
State varchar (50),
Country varchar (50),
Phone_no bigint (10)
);
