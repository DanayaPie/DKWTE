# Don't Know What To Eat

## Project Description

Don’t Know What To Eat is a web application that randomly selects a restaurant based on the user address and radius specified by the user. When the user types in the address or allows location access and clicks the ‘Eat’ button, the application will randomly select a restaurant. All users can view all the reviews about the restaurant by clicking the ‘Display Reviews’ button. The users can also sign up and log in as a member to write their reviews by clicking the ‘Add Review.’ When users leave reviews, the admins have the authority to delete any relevant or inappropriate reviews.

<!-- **EC2 link:** http://ec2-3-138-126-45.us-east-2.compute.amazonaws.com:5050/ -->

## Technologies Used

- Java
- Spring Framework (AOP, ORM)
- Spring MVC
- Hibernate
- AJAX
- H2
- Apache (lang3, surefire)
- Log4J
- PostgreSQL
- SQL
- Angular
- HTML
- CSS
- TypeScript
- Redux
- JUnit
- Selenium

## Features

- All users can get a randomly selected restaurant in their area and view all reviews on the restaurant.
- Users can sign up to become a member to write their comments/reviews about the restaurant.
- Admin can get a randomly generated restaurant, view reviews about the restaurant, and write reviews.
- Admin can search the reviews by restaurant name, review id, review title, and subject.
- Admin has the authority to delete inappropriate or irrelevant reviews.
- Both admins' and members' private information is securely stored in the database where the password is hash.

To-do list:

- Allow the user to be able to get a randomly generated restaurant by address.
- Utilize SonarCloud to detect bugs, vulnerabilities, code smells, and get a code coverage report.
- Wow improvement to be done 2

## Getting Started

<!-- **Via EC2:**

http://ec2-3-138-126-45.us-east-2.compute.amazonaws.com:5050/ -->

<!-- **Local Application:** -->

_Backend:_

1. Be sure to have the Java 8 runtime environment installed.
2. Clone the backend repository: ```https://github.com/DanayaPie/DKWTE.git```
3. Set the runtime environment:
   - Application: in the **src/main/resources** package: Set up the runtime enviroment in the _'application.properties'_.
   - Testing: in the **src/test/resources** package: Set up runtime enviroment in the *'application.properties'*.
4. Set up the database: for application and testing
   - (4.1) Application: in the **src/main/resources** package: Change the **_hibernate.ddl-auto_** in the _'application.properties'_ to create, validate, update as needed to create, or manage the database.
   - (4.2) SQL: Create a schema name **dwte**

_Frontend:_

1. Be sure to have Angular 2+ installed. See angular setting up for help. ```https://angular.io/guide/setup-local```
2. Clone the fronted repository: ```https://github.com/DanayaPie/DKWTE.git```
3. Install the **node_modules** by using ```npm install```

<!-- ## Usage

> Here, you instruct other people on how to use your project after they’ve installed it. This would also be a good place to include screenshots of your project in action. -->

## Contributors

- Damilare Olaleye
- Danaya Chusuwan
- Ashli O'Neal
- Jahlil James
- Kibru Kassa

<!-- ## License

This project uses the following license: [<license_name>](link). -->
