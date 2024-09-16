# L-R-F
# Description
It is a simple registration and login system created using node.js, postgreSQL, express. It allows users to create an account and log in.

# Features
Registration form,login form,simple main page with navigation ,user authentication.

# Prerequisites
Before you start, install node.js and postgresSQL.

# To enter into the terminal, enter the following:
npm init -y
npm install express pg bcryptjs jsonwebtoken dotenv

# Create a database in PgAdmin
First, create a database named users, then create a table called users and enter the following code:
CREATE TABLE users (
  id SERIAL PRIMARY KEY,
  username VARCHAR(100) NOT NULL UNIQUE,
  email VARCHAR(100) NOT NULL UNIQUE,
  password VARCHAR(255) NOT NULL
);

# Steps
After creating the database, proceed to create a "public" folder in Visual Studio.
Inside the "public" folder, create the following subfolders: css, js, and html .
Next, in the "css"  folder, create a file named styles.css; 
In the "js" folder, create a file name scripts.js;
inside the "html" folder, create files registration.html, login.html, and index.html.
Afterward, create the files server.js and .env.
