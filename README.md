# Expense Tracker App

This repository contains a simple web application for managing and tracking personal expenses. The Expense Tracker Application allows users to easily record their expenses, categorize them, and gain insights into their spending habits.

## Features

The Expense Tracker Application comes with the following features:

- Add new expenses: Name, amount, date, category.
- Edit and delete existing expenses.
- View expenses in paginated table.
- Filter by month, year, category.
- Total expense amount for selected filter.
- Customize expense categories.
- Export expenses to CSV.

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

- Clone the repository: `git clone https://github.com/ahladach/ExpenseTracker.git`
- Open the project in your preferred Java IDE.
- Ensure MySQL is installed and running.
- Create a new MySQL database for the application.
- Update `application.properties` with your MySQL database URL, username, and password.
- Build and run the application using Maven: `mvn spring-boot:run`
- Access the Expense Tracker Application via http://localhost:8191 in your web browser.

## Project Structure

The project follows a standard Spring Boot project structure:

- 'src/main/java': Java source code.
- 'src/main/resources': App configuration and Thymeleaf templates.
- 'src/main/resources/static': CSS and images.
