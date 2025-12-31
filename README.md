CS Project Notes
This project uses a mysql database and flask. It compares team and player ratings and also has a win predictor that is displayed on a webpage.
Database
a. MySQL
b. Database name: database_small
c. SQL File: cs_proj.sql
d. To create db: mysql -u root -p database_small < cs_proj.sql

HTML Files
a. Project location: <work_area>/cs_proj/
b. HTML files: <work_area>/cs_proj//templates/
c. List of html files
i. Index.html
ii. searchteams.html
iii. searchplayer.html
iv. addplayer.html
v. remplayer.html

Python code
a. <work_area>/cs_proj/webpage_sql.py
b. Required packages
a. flask
b. mysql.connector
c. Preferable to work in a virtual env

Project features
a. List teams with players and the teams rating
b. Compare two teams and predict win probability for each
c. List all players in the database
d. Compare two players across all their attributes
e. Add or remove a player from the player database
f. Exchange two players across teams
