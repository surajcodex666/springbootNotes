
# Programming lang vs Technology vs Framework


## Q) What is a programming language ?

=> programming lang contains set of instructions 
ex: C, C++, Java, C#
=> Every programming language will follow set of syntaxes
=> using programming language We can develop 
                applications/toos/software/technologies/Framework
=> we can develop only stand alone applications                 


## Q) What is Technology?

=> Technology is a software which is developed by using programming language
        ex: srvlets, JSP, JDBC
=> Technologies are used to resolve common problems/ address common requirements/to simplify our tasks
=> By using technologies we can develop our applications    


## Q) What is Framework?

=> Framework is a semi developed software
=> It provides common logics required for application development
                ex:
                        1) Capture form data
                        2) Validate form data
                        3) Create connection pool
                        4) DB CRUD etc.....

=> It provides re-usable components
=> For ex, every Java Developer should write below lines of code to perform DB operation

Class.forName("");
DM.getConn("");
createStatement()
executeQuerry()
process ResultSet()
close connection


### NOTE - If we are writing same code for multiple times then it is called 
a boiler plate code / redundant code.


=> To avoid duplicate code/ common logic implementation, Frameworks came into picture.

                Project = Business Logics + Common Logics

=> Frameworks provides common logics required for the projects so that we only have to focus on only business Logic development
=> It will improve developers productivity, can do more work in less time

                ex: 
                JAVA=> Hibernate, Spring, Struts, Spring Boot
                .Net=> WCF
                Python=>  DJango, Flask
                Salesforce=> Lightning etc......


### NOTE - Frameworks will be developed by using Programming Language only.

---

## Tools :

=> Tools are used to automate manual work
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
