# Programming lang vs Technology vs Framework

## Q) What is a programming language ?

a) programming lang contains set of instructions 
ex: C, C++, Java, C#
b) Every programming language will follow set of syntaxes
c) using programming language We can develop 
                applications/toos/software/technologies/Framework
d) we can develop only stand alone applications                 


## Q) What is Technology?

a) Technology is a software which is developed by using programming language
        ex: srvlets, JSP, JDBC
b) Technologies are used to resolve common problems/ address common requirements/to simplify our tasks
c) By using technologies we can develop our applications    


## Q) What is Framework?

a) Framework is a semi developed software
b) It provides common logics required for application development
                ex:
                        1) Capture form data
                        2) Validate form data
                        3) Create connection pool
                        4) DB CRUD etc.....

c) It provides re-usable components
d) For ex, every Java Developer should write below lines of code to perform DB operation

Class.forName("");
DM.getConn("");
createStatement()
executeQuerry()
process ResultSet()
close connection


### NOTE - If we are writing same code for multiple times then it is called a boiler plate code / redundant code.


e) To avoid duplicate code/ common logic implementation, Frameworks came into picture.

                Project = Business Logics + Common Logics

f) Frameworks provides common logics required for the projects so that we only have to focus on only business Logic development
g) It will improve developers productivity, can do more work in less time

                ex: 
                JAVA=> Hibernate, Spring, Struts, Spring Boot
                .Net=> WCF
                Python=>  DJango, Flask
                Salesforce=> Lightning etc......


### NOTE - Frameworks will be developed by using Programming Language only.

## Tools :

a) Tools are used to automate manual work
        
        Ex: 
                1) Maven
                2) JIRA
                3) JENKINS
                4) JMETER
                5) POSTMAN
                6) SONARQUBE etc....
                
---
# Application Architecture


Project = Frontend + Backend + Database

Frontend : Presentation Logic / User Interface Logic

        Frontend Techstack:
                1) HTML & CSS
                2) Java Script
                3) Bootstrap
                4) Angular (or) React JS (or) Vue JS

Backend : Web Layer(REST APIs) + Business Layer + Intergation layer + DAO layer

        Backend Techstack:
                1) Java & J2EE
                2) Spring Core
                3) Spring boot
                4) JPA
                5) REST APIs
                6) JSON
                7) Microservices
                8) Security
                9) Kafka + Redis
                10) Reactive programming

Database : Persistant Store
        ex: Oracle, MySQL, Postgres, Mongo DB etc....

Tools : Maven + Git Hub + Log4J + JUnit + Jenkins + SonarQube + JIRA + Docker + Kubernetes  

Cloud Platforms : AWS / Azure / GCP

## Architecture Types 
### 1) Monolith Architecture 
a) developing all requirements as one application
b) outdated, bcz maintenance will be difficult
c) even for small changes baar baar poora project deploy krna pdega
d) ek functionality me change krenge to baaki functons pr bhi effect hoga
### 2) Microservices Architecure
a) divide and conquer
b) divide the project into diff-diff parts 
c) maintenance will be very easy
d) loosely coupled APIs
e) easy deployment 
f) no single point of failure

