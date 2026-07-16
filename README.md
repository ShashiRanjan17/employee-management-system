\# Employee Management System



A full-stack CRUD application built using React.js (frontend) and Spring Boot (backend), with MySQL as the database.



\## Features

\- Add, View, Update, and Delete employee records

\- REST API built with Spring Boot

\- React frontend consuming the API via Axios

\- MySQL database integration using Spring Data JPA



\## Tech Stack

\- Frontend: React.js, Axios, Bootstrap

\- Backend: Spring Boot, Spring Data JPA

\- Database: MySQL



\## Architecture

React (port 3000) → REST API calls via Axios → Spring Boot (port 8080) → Spring Data JPA → MySQL Database



\## How to run

1\. Clone the repository

2\. Setup MySQL database `employee\_management\_system`

3\. Update database credentials in `springboot-backend/src/main/resources/application.properties`

4\. Run backend: `cd springboot-backend \&\& mvn spring-boot:run`

5\. Run frontend: `cd react-frontend \&\& npm install \&\& npm start`

6\. Open `http://localhost:3000` in your browser

