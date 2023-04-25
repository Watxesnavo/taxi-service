# taxi-service
The Taxi-Service project is a Java-based web application that provides a platform for managing the services related to a taxi service company. The project uses a MySQL database to store and retrieve data related to cars, drivers, and car manufacturers. The project includes controllers for login and logout, creating new cars and drivers, and assigning drivers to cars. Additionally, it includes features for creating car manufacturers. And you can remove any of them.

Requirements:

The following technologies and tools are required to run the Taxi-Service project:

- Java Development Kit (JDK) 11 or higher version
- Apache Tomcat Server 9 or higher version
- MySQL Community Server 8.0 or higher version
- MySQL Connector/J 8.0 or higher version
- Java Servlet API
- IDE (Integrated Development Environment) such as IntelliJ IDEA, Eclipse, or NetBeans

👀Installation;

To install and run the Taxi-Service project on your local machine, please follow these steps:

1. Clone the project from the GitHub repository.
2. Open the IDE and import the project as a Maven project.
3. Configure the database connection by providing your credentials and the database name to the ConnectionUtil class, located in the src/main/java/taxi/util folder.

jdbc.url=jdbc:mysql://localhost:3306/<DATABASE_NAME>?serverTimezone=UTC

jdbc.username=<YOUR_USERNAME>

jdbc.password=<YOUR_PASSWORD>

4. Build the project using Maven.
mvn clean package
5. Deploy the generated WAR file to the Apache Tomcat Server.
6. Access the application at the following URL: http://localhost:3306/index.

Usage:

The Taxi-Service project provides a web interface that allows users to perform the following actions:

- Login and Logout: Users can login to the application by providing their username and password. To register driver just go /drivers/add, it's same as register. Logged-in users can logout by clicking the logout button.
- Create New Car: Users can create a new car by providing its manufacturer and model. The car form also includes fields for selecting the car driver.
- Create New Driver: Users can create a new driver by providing their name, license number, and create username and password.
- Add Driver to Car: Users can assign a driver to a car by selecting the driver from the /cars/drivers/add.
- Create Car Manufacturer: Users can create a new car manufacturer by providing its name, and country.
- Delete Any of Them: Users can delete any of the entities (cars, drivers, car manufacturers) created by them by selecting the delete button next to their name on the corresponding list page.


🎯Functions:

  links:
  - /drivers/add (create new driver)
  - /drivers (show all the drivers)
  - /cars/add (create new car)
  - /cars (show all the cars)
  - /manufacturer/add (create new manufacturer for the car)
  - /manufacturers (show all the manufacturers)
  - /cars/drivers/add (add driver to car)
  - /login/logout (logging feature)

⚙️Project structure:
- models
- dao
- controllers
- services
- filter

Imports:
<img width="494" alt="Captura de pantalla 2023-04-23 a las 19 49 05" src="https://user-images.githubusercontent.com/112902418/233856233-f75e555b-aabd-4bdd-a93a-4e4942b31084.png">


Conclusion;

The Taxi-Service project demonstrates the use of Java Servlet API for creating a web application that provides services related to a taxi service company. Its simple and user-friendly interface allows users to easily manage cars, drivers, and car manufacturers. With this project, you can learn how to work with a MySQL database, and how to write controllers that handle the user requests and responses.

For more information, please visit the project repository on GitHub.
