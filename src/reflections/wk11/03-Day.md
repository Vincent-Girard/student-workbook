# Feb-24-2021 WebAPI's > SQL Injection

## What is SQL injection?

It is an attack that would give an enemy complet control over yoru web application database simply by insterting arbitrary SQL code into a database query. Luckily this isn't somethign that is super hard to prevent and rather elementary my dear watson. 

## 2. What are methods SQL injection can be done by? 

Retrieving hidden data- this is where you modify a query and return results that are not meant to be seen. 

Subverting application logic - this is where you change the query to mess with the applications logic

Union Attacks - This is retrieving different data from different db tables 

Examining the db - this is where you can get info regarding the structure and version of the db

Blind SQL injeciton - this is where results of a query you control do not turn in the applications responses


## 3. How can we detect and sanitize SQL injection attacks? 

Intrusion detection systems - This is both network and host based, this can configured to detect SQL injection attacks. The network based IDSes will monitor all of the connections to the db server and show you anything that is irregular. 

Host based will monitor the web server logs and also alert you if something strange is going on 

## Afternoon Project 

https://github.com/Vincent-Girard/taskmasterbackend