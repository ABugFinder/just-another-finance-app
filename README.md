# just-another-finance-app

## About The Project
Personal project by ABugFinder to keep coding skills sharp and manage personal finance health more efficiently. This app is designed to track and categorize expenses, monitor monthly incomes and expenditures, and provide a clear and simple overview of financial health.

The goal is to develop a user-friendly interface that allows for easy input and categorization of various expenses, along with tracking monthly income. This will help in gaining a better understanding of spending patterns and overall financial health.

### Built With
This project is built using a combination of modern technologies to ensure efficiency, scalability, and ease of use:
- **Backend**: Nest.js
- **Frontend**: Angular
- **Database**: MySQL

## Getting Started

### Prerequisites
- Node.js
- Angular CLI
- Nest.js CLI
- MySQL

### Installation
1. **Clone the repo:**
   ```
   git clone https://github.com/your_username/just-another-finance-app.git
2. **Install NPM packages for the backend:**
    ```
    cd just-another-finance-app/backend
    npm install
    npm install -g @nestjs/cli (only if you need to add more modules)
    ```
    For more details, see [nest.js docs](https://docs.nestjs.com/first-steps)
3. **Install NPM packages for the frontend:**
    ```
    cd ../frontend
    npm install
    npm install -g @angular/cli (only if you need to add more modules)
    ```
    For more details, see [angular docs](https://angular.io/quick-start)
4. **Install MySQL**
    [Download & install MySQL Community](https://dev.mysql.com/downloads/mysql/) and then run:
    ```
    mysql -u root -p
    CREATE DATABASE your_database_name;
    ```
    ```
    CREATE USER 'new_user'@'localhost' IDENTIFIED BY 'your_password';
    GRANT ALL PRIVILEGES ON your_database_name.* TO 'new_user'@'localhost';
    FLUSH PRIVILEGES;
    ```
    *NOTE:* **Replace** new_user, your_password, and your_database_name with **your own values**.

    **Additional considerations**

    * MySQL Client: You can use a graphical client like MySQL Workbench for easier management of your database.
    * Project Settings: Make sure you update the database connection settings in your project (such as the Nest.js configuration file) with the correct details (database name, user, password).
    * Installation on Different Operating Systems: The installation process may vary slightly depending on whether you are on Windows, Mac or Linux.
    * Security: Be sure to follow security best practices, such as using strong passwords and limiting database user privileges.



5. **Start the backend server:**
    ```
    cd backend
    npm run start
6. **Start the frontend application:**
    ```
    cd ../frontend
    ng serve
### Usage
You click on buttons and app goes brrrrrr
### License

©ABugFinder - All rights reserved. No part of this project may be used, reproduced, distributed, or modified without explicit permission from the author.

Project Link: https://github.com/your_username/just-another-finance-app