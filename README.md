# Taxi-Service

This program simulates the work of a taxi service with a driver authentication system.  
After launching the application, you first need to register and log in.  

Then, you can:  
- Create new Driver or delete existing 
- Create new Car or delete existing
- Create new Manufacturer or delete existing
- Add Driver to Car
- Display All Drivers
- Display All Cars
- Display All Manufacturers

### Implementation details:
This project is based on a 3-tier architecture:  
1. Data access layer (DAO)  
2. Application layer (Service)  
3. Presentation layer (Controllers)

### Technologies used:  
- Apache Tomcat
- JDBC
- MySQL
- Servlet 
- JSP
- JSTL
- HTML
- Maven 

### Recommendations for running the application:  
1. Install Apache Tomcat  
2. Install MySQL and MySQL Workbench 
3. Clone the project to your IDE
4. Use a script from the file taxi-service\src\main\resources\init_db.sql to create a database
5. Open the class taxi-service\src\main\java\taxi\util\ConnectionUtil.java and replace the value of the  
   constants: URL, USERNAME, PASSWORD, JDBC_DRIVER with your data  
6. Open the file taxi-service\src\main\resources\log4j2.xml and   
   replace the value of the parameter "fileName" with your absolute path to the log file 
7. Configure Apache Tomcat (Add New Configuration -> TomCat -> Local -> Fix -> taxi-service:war exploded -> OK)
8. Run the application


