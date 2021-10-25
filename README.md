## General info
I have created this "Taxi service" project to demonstrate my expertise in Java Core, Object-oriented programming, SOLID concepts, JDBC and WEB-technology.
In this web-application we can registrate or authenticate a driver, create new car or manufacturer that will be added to the DB. Moreover, in this app you 
can add driver to a car and look at the list of all cars that our driver use.

# ❓ How to use it:
1️⃣ Crate new driver - it's you account (login and password).

2️⃣ Login.

3️⃣ You can 
- create new car, manufacturer, add manufacturer to car, driver to car, 
- look all drivers, cars and others,
- also you can delete some information

## Technologies
In project these technologies have been used:
```
* Maven 3.1.1
* Java 11
* DI (custom injector)
* MySQL
* Tomcat 9.0.54 (You don't have to use Tomcat version 10+).
* Javax servlet API 4.0.1
* JSTL 1.2
* Log4j2
```

##🔧  To start a project you must have:
1️⃣ IDE for Java.
2️⃣ MySQL or other DBMS (but you mush correct class ConnectionUtil and your DB).
3️⃣ Create your database using init_db.sql file located in src/main/resources/init_db.sql
4️⃣ Configure connection to DB for:
src/main/java/mate/util/ConnectionUtil.java
```java
    private static final String URL = "url DB";
    private static final String USERNAME = "YOUR_USERNAME";
    private static final String PASSWORD = "YOUR_PASSWORD";
```
5️⃣ Run Tomcat 🚀

Otherwise you can just click here: https://my-taxiservice.herokuapp.com/login
