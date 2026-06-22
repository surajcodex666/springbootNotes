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

# Architecture Types 
## 1) Monolith Architecture 
        a) developing all requirements as one application
        b) outdated, bcz maintenance will be difficult
        c) even for small changes baar baar poora project deploy krna pdega
        d) ek functionality me change krenge to baaki functons pr bhi effect hoga
## 2) Microservices Architecure
        a) divide and conquer
        b) divide the project into diff-diff parts 
        c) maintenance will be very easy
        d) loosely coupled APIs
        e) easy deployment 
        f) no single point of failure

## Types of frameworks 
### 1) Frontend Framework : 
                to develop user interface in the project
                ex: Angular
### 2) Web Frameworks :
                to develop web layer in the project 
                ex: Struts(Outdated)
### 3) ORM Frameworks : 
                to develop persistance layer in the project 
                ex: Hibernate 

## Struts Framework Disadvantages :                

                a) By using Struts we can develop only Web Layer in the project (Controllers)
                b) By using hibernate we can develop only Data Access Layer (Persistence Layer)

## Notes : To overcome the problems of Struts framework, Spring Framework came into market.

## Spring Framework :

                a) Spring Framework is called as Application Development Framework
                b) By using Spring Framework we can develop end to end application
                c) Spring is free & open source framework
                d) Spring framework is developed in Modular fashion
                e) Spring framework means collection of modules

## Spring Modules :

                1) Spring core
                2) Spring context
                3) Spring JDBC
                4) Spring ORM
                5) Spring AOP
                6) Spring Web MVC
                7) Spring security
                8) Spring social
                9) Spring Batch
                10) Spring Data JPA
                11) Spring REST
                12) Spring Cloud

### NOTE : Spring is a very flexible framework. It will not force to use all modules. We can choose based on our requirements.

                a) Spring is a versatile framework(Easily it can be integrated with other frameworks)
                b) The current version of Spring Framework 7.0
                c) Spring framework is under license of VM ware

## 1) Spring core : It is base module in the spring framework
=> Spring core module providing fundamental concepts of spring framework 

                1) IOC container(Inversion of Control)
                2) Dependency Injection
                3) Bean life cycle
                4) Bean Scopes
                5) Autowiring...   

## 2) Spring Context : It will deal with configurations reequired for our spring application

## 3) Spring AOP : Aspect Oriented Programming 
=> AOP is used to seperate business logic & secondary logics in the project     

                ex: Security, Logging, Tc, Auditing, Exception handling...

### NOTE : If we combine business logic and secondary logic together then we'll face maintenance issues  

## 4) Spring JDBC : Spring JDBC is used to simplify Database communication logic
=> Using Spring JDBC we can directly execute the querry, we dont have to write all the other connections like we do in java JDBC

## 5) Spring Web MVC : It is used to develop both Web application & Distribuited Application

                => Web Application (Customer to Business)
                        ex: Gmail.com, Facebook.com etc
                => Distribuited Applications (Business to Business) / Web Services (or) RESTful Services
                        ex: IRCTC, MakeMyTrip   

## 6) Spring ORM(Object Relation Manager)
=> Spring Framework Having Integration with ORM Frameworks
                ex: Spring ORM, Spring Data JPA etccc..

### NOTE : JDBC will represent data in text format whereas Hibernate ORM will represent data in objects format.

## 7) Spring Security : 

                a) Security is very cruicial for every application
                b) USing spring security We can implement Authentication & Authorization
                c) Spring security with OAuth2.0
                d) Spring Security with JWT (JSON Web Tokens)

## 8) Spring Batch : Batch means bulk operation 

                a) Reading data from excel file and store it into database table
                b) Sending Monthly Statements to customers in email
                c) Sending reminder to customers as Bulk SMS

## 9) Spring cloud : It Provides some common tools to quickly build distribuited systems.    

                a) Provides service register to register microservices
                b) Provides Load balancer to balance the load of our application
                c) Provides Monitoring Facility
                d) PRovides API gateway to have single entry point for all our APIs
                e) Provides Circuit Breaker(Fault tolerant Systems)
                f) Distribuited Messaging 
                g) Routing

## 10) Spring Test : It provides Unit Test framework  

# Spring core

                a) Spring core module is all about managing dependencies among the classes with loosely coupling
                b) In project we will develop several classes. All those classes we can categorize into 3 types -
                        1) POJO
                        2) Java Bean
                        3) Component

## What is POJO? (Plain Old Java Object)
=> Any Java class which can be compiled by using only JDK software is called a POJO class   

                ex1: Below class is a valid pojo
                class Demo{
                        int id;
                        String name;
                }

                ex2:
                class Demo2 extends Thread{
                        int id;
                        String name;
                }

                ex3:
                class Demo3 implememts Runnable{
                        // run method 
                } 