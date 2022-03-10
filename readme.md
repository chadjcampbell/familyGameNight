# Family Game Night

#### Video Demo:

#### App deployed on Heroku:
https://fgn-cs50.herokuapp.com/

#### Description:
Family Game Night is a web app developed by myself (Chad Campbell) as a final project for Harvard CS50x: Intro to Computer Science. The project uses micro framework Flask with Python and Jinja syntax for some logic to show database information on the apps routes. HTML, CSS with bootstrap, and Javascript were used on the front end. SQLite3 was used for the database. *Note: SQLite3 does not store information persistantly on Herokus free service.*

#### Pages:

###### Index:
This is the landing page that just greets the user and explains the purpose of the app, if they are logged in. If not they are redirected to login.

###### Login/Register:
These forms are validated with SQL queries and a hash for the password made using werkzeug.security. Then the user id will be the primary key for all other databases.

###### Family/Games:
These forms and data tables INSERT and show SELECTED data for the apps other services, the leaderboard/history and the "wheel".

###### History/Leaderboard:
The forms on this page only allow inputs from the data tables controlled on the Family or Games page, but they INSERT into their own table. This way games and family members can be added and removed while the historical data here will stay.

###### Spin the Wheel:
