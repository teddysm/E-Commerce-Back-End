# E-Commerce Back End

This is the back end for an e-commerce site.

<br>

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [References](#references)
- [Links](#links)
- [Features](#features)
- [Installations](#installations)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)

<br>

## Description

- This program will start with a menu and user can select from 8 options
- After each selection, program will generate/edit information and prompt user for another option

<br>

## Usage

- Use Mysql to run the schema and the seed SQL files
- Start the program with 'npm start'
  ![Screenshot](./assets/Screenshot1.png)
  ![Screenshot](./assets/Screenshot2.png)
  ![Screenshot](./assets/Screenshot3.png)
  ![Screenshot](./assets/Screenshot4.png)
  ![Screenshot](./assets/Screenshot5.png)
  ![Screenshot](./assets/Screenshot6.png)

<br>

## Links

- Github page: https://github.com/teddysm/E-Commerce-Back-End
- Video walkthrough: https://drive.google.com/file/d/1uj-EOwVwclUagV6Fe3fXSDA2Wu3r2tqS/view
- Or: https://app.screencastify.com/manage/videos/MuiYre8Zaje3H612S9hl

<br>

## Features

- User can view all employees, Add Employee, Update Employee Role, View All Role, Add Role, View All Department, and Add Department.

<br>

## Installations

- Users need to install the dependencies with the command "npm i".
- Users need to install Insomnia or similar software.

<br>


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

