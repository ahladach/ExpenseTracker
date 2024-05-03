# Expense Tracker App

This repository contains a simple web application for managing and tracking personal expenses. The Expense Tracker Application allows users to easily record their expenses, categorize them, and gain insights into their spending habits.

## Features

The Expense Tracker Application comes with the following features:

Add new expenses with details like name, amount, date, and category
Edit and delete existing expenses
View a list of all expenses in a paginated table
Filter expenses by month, year, and category
See the total expense amount for the selected filter
Customize expense categories according to your needs
Export expenses to a CSV file for further analysis or record-keeping

## Technologies Used

The Expense Tracker Application is built using the following technologies:

Java 17
Spring Boot 3
Spring Data JPA
Thymeleaf
MySQL
Maven
HTML, CSS, and Bootstrap

## Getting Started

To run the Expense Tracker Application on your local machine, follow these steps:

Clone the repository: git clone https://github.com/your-username/expense-tracker-app.git
Open the project in your preferred Java IDE.
Make sure you have MySQL installed and running on your machine.
Create a new MySQL database for the application. You can use the following 
Update the application.properties file in the src/main/resources directory with your MySQL database URL, username, and password.
Build and run the application using Maven: mvn spring-boot:run
Open your web browser and navigate to http://localhost:8191 to access the Expense Tracker Application.

## Project Structure

The project follows a standard Spring Boot project structure:

'src/main/java' contains the Java source code
'src/main/resources' contains the application configuration files and Thymeleaf templates
'src/main/resources/static' contains the static assets (CSS and images)
