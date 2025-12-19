1. Install HomeBrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

2. # Update Homebrew to ensure you get the latest version
brew update

3. # Install MySQL
brew install mysql

4. # Start the MySQL background service
brew services start mysql


User - root
Password - 'password'



5. DB Creation

CREATE DATABASE personal_db;
USE personal_db; - Use this database

We are using personal_db

6. SHOW DATABASES;

7. DROP DATABASE database_name;

8. CREATE DATABASE IF NOT EXISTS database_name; -> SQL CREATE DATABASE with IF NOT EXISTS Clause

9. Rules for Naming a Database
When naming your database in SQL, it is important to follow standard rules to avoid errors:

Use only letters, numbers, and underscores (_).
Don't use spaces or special characters like @, #, %, etc.
Stick to lowercase or snake_case format (e.g., school_system).
Make sure the database name is unique in your system.
Example: Valid Database Names
Following are some examples of names that follow the proper rules:

    CustomerDB
    employee_data
    inventory2025


Invalid Database Names
Following are some examples of names that break the naming rules and should be avoided:

    123database (starts with a number)
    user data (contains a space)
    db@info (contains a special character)





