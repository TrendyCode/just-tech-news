# just-tech-news

## Description
Just Tech News is the back end application for Just Tech News —a tech news website where users can post, upvote, and comment on links to news articles. It uses Sequelize, to simplify MySQL queries. It also uses password hashing so that users can create secure passwords. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Tests](#tests)

## Installation

Install Sequilize. Follow the instructions on their site https://sequelize.org/
Install Dotenv. Follow the instructions on their site  https://www.npmjs.com/package/dotenv
Install bcrypt. Follow the instructions on their site https://www.npmjs.com/package/bcrypt

Initialize Node.js by entering the following command in the terminal:
    
    npm init --y

Install Express.js and the MySQL2 node packages by entering the following command in the terminal:
   
    npm install express mysql2
    
    
Then visit https://dev.mysql.com/downloads/mysql/ for MySQL download instuctions. 
Verify the download is complete by entering the following command in the terminal:
    
    mysql -v
    
Enter the following command into the terminal to initiate the MySQL Shell and make edits:
    
    mysql -u root -p
    
Enter your MySQL password when prompted. Then, at the MySQL CLI prompt, switch to the election database by typing the following command:
    
    USE just_tech_news_db;
    
Then rebuild and seed the database by running the following commands:
    
    source db/schema.sql


## Usage

This is the back-end of the application. Feel free to design the interface of your choice. 

## Credits

UCF Full Stack Coding Bootcamp


