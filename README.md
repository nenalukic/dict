This program is an dictionary where you can add a new word and translation in the list.You can save and delete the same.

You need a database and you can create then in the PostgreSQL. 

Start like this:
- Login to database: psql postgres postgres
- Create database: create database dict;
- Create user: create user dict with password 'abc123';
- Grant user rights: grant all privileges on database dict to dict;
- Logout: \q

- Login to new database: psql dict dict

Then write in the terminal python dict.py to start the program.