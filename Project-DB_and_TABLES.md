# DBMS-PROJECT-AIRLINE TICKECT BOOKING

### CREATING DATABSAE AND TABLES

### 01- CREATE DATBASE

~~~sql
 CREATE DATABASE AirlineDB;
~~~

### 02- USE DATABASE

~~~sql
 CREATE DATABASE AirlineDB;
~~~

### 03- CREATE TABLE AIRPORTS

~~~sql
CREATE TABLE Airports (
    -> Airport_Code VARCHAR(10) PRIMARY KEY,
    -> Airport_Name VARCHAR(100),
    -> City VARCHAR(50)
    -> );
~~~

### 04- CREATE TABLE FLIGHTS

~~~sql
CREATE TABLE Flights (
    -> Flights_ID VARCHAR(10) PRIMARY KEY,
    -> Airline_Name VARCHAR(50),
    -> Total_Seats INT
    -> );
~~~
