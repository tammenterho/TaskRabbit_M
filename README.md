# TaskRabbit
Small Tasks, Big Impact
TaskRabbit is a user-friendly web application that connects individuals seeking help with those offering assistance. Users can easily post tasks if they need assistance or earn a small income by browsing through available opportunities and performing tasks. With a profile page showcasing user statistics and reviews, as well as an interactive Google Maps integration, TaskRabbit creates a community where tasks are accomplished efficiently and collaboratively.

This project uses a combination of front-end, back-end, and cloud technologies. On the front-end, the project uses JavaScript as its main programming language, React as the main library for building user interfaces, React Redux for state management, RTK Query for data fetching, and Bootstrap for responsive web design. On the back-end, the project uses Java as the main programming language, Spring Boot as the main framework, and MySQL as the database. The project is deployed on the AWS cloud platform and utilizes various services such as RDS for the MySQL database, Elastic Beanstalk for deployments, and S3 for storing static assets.

## Installation

- Clone the repository  
`git clone git@github.com:arska2/TaskRabbit.git`  
- Use taskrabbit.sql (in root directory of this repository) to set up the MySQL database locally  
`mysql -u <username> -p <database_name> < taskrabbit.sql`
- update your database password and username to application.properties
- start server (run in server folder)   
    `mvnw spring-boot:run`   
- Install front-end dependencies   
`cd client`  
`npm i`  
- Start React App  
`npm start`

The back-end database API is hosted on localhost:8080, and the front-end React app can be found at localhost:3000.