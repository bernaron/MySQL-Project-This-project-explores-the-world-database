# MySQL-Project-This-project-explores-the-world-database
# MySQL World Database Project

This project explores the [World database](https://dev.mysql.com/doc/index-other.html), which contains information about countries, cities, and other geographical and demographic data. The purpose of this project is to answer specific questions using SQL queries.

## Project Objectives

The project addresses the following questions:
1. **City with the largest population**.
2. **How many cities are in the USA**.
3. **Country with the highest life expectancy**.
4. **Top 10 high-populated cities**.
5. **Cities with a population of more than 2 million**.

---

## Prerequisites

To run this project, ensure the following:
- MySQL server is installed.
- The World database is loaded into your MySQL instance. You can download it [here](https://dev.mysql.com/doc/index-other.html).

---

## Questions and Queries

### 1. **City with the Largest Population**
Query:

SELECT Name, Population 
FROM city 
ORDER BY Population DESC 
LIMIT 1;

![image](https://github.com/user-attachments/assets/a66f5e4b-b448-41e7-b06f-516bc9474371)

## City with the highest life expectancy
SELECT Name, LifeExpectancy 
FROM country 
ORDER BY LifeExpectancy DESC 
LIMIT 1;

![image](https://github.com/user-attachments/assets/965f9bd9-5fac-4a3f-b84f-714075063f68)

##Top 10 high populated cities

SELECT Name, Population 
FROM city 
ORDER BY Population DESC 
LIMIT 10;

![image](https://github.com/user-attachments/assets/2ec87c1c-0d4d-4482-ada0-0ce93215a7bc)


### Cities with population over 2million
SELECT Name, Population 
FROM city 
WHERE Population > 2000000 
ORDER BY Population DESC;

![image](https://github.com/user-attachments/assets/45ecff9f-62ff-4ed2-adff-7632f55e5545)


