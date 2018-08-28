1.git clone

2.Run npm init command in terminal that will create package.json file for your project.

3) Install Express Framework module with the following command:


npm install express -save
1
npm install express -save
4) Install express-validator module that will be used for form validation


npm install express-validator -save
1
npm install express-validator -save
5) Install body-parser module

body-parser module is used to read HTTP POST data. It’s an express middleware that reads form’s input and store it as javascript object.


npm install body-parser -save
1
npm install body-parser -save
6) Install method-override module

This module let us use HTTP verbs such as PUT or DELETE in places where they are not supported. This module provides different ways of overriding like overriding using header, overriding using query value, or through custom logic. In this CRUD application, we will be using the custom logic of overriding.


npm install method-override -save
1
npm install method-override -save
7) Install express-flash module

Flash messages are shown for some time and cleared after being displayed to the user. They are mainly used when we have to redirect to next page and show certain message like success message or error message. Flash messages are store in session.


npm install express-flash -save
1
npm install express-flash -save
8) Install cookie-parser & express-session modules

Flash messages are stored in session. So, we also have to install and use cookie-parser & session modules.


npm install cookie-parser -save
npm install express-session -save
1
2
npm install cookie-parser -save
npm install express-session -save
9) Install EJS templating engine


npm install ejs -save
1
npm install ejs -save
10) Install MySQL module with the following command:


npm install mysql -save
1
npm install mysql -save
11) Install express-myconnection module

Express middleware to provide consistent API for MySQL connection. It can auto close/release mysql connection. Using this module, the connection can be accessed anywhere in router.


npm install express-myconnection -save
1
npm install express-myconnection -save
12) We will now create a new MySQL database. Let us name the database as ‘test‘.


create database test;
1
create database test;
Then, we will create a new table in database ‘test’. Let us name the table as ‘users‘.


use test;

CREATE TABLE users (
id int(11) NOT NULL auto_increment,
name varchar(100) NOT NULL,
age int(3) NOT NULL,
email varchar(100) NOT NULL,
PRIMARY KEY (id)
);
1
2
3
4
5
6
7
8
9
use test;
 
CREATE TABLE users (
id int(11) NOT NULL auto_increment,
name varchar(100) NOT NULL,
age int(3) NOT NULL,
email varchar(100) NOT NULL,
PRIMARY KEY (id)
);
