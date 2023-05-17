# E-Commerce Back End Site
  
## Description
  
The purpose of this project was to use the Express and MYSQL2 npm packages to build the back end for an e-commerce site. The project utilizes RESTful routes to navigate a database to get, post, update, and delete data within the database.

 ## Table of Contents 
   - [Installation](#installation)
   - [Usage](#usage)
   - [Contact Info](#contact-info)


## Installation
  
- git clone repo
- cd ../to/the/file/path
- code .

## Usage 

- Ensure that node is installed on your computer. Go to [Node's Website](https://nodejs.org/en) to find the program to download
- Download the LTS version 
- In your command line, type **npm install** to install all the node packages
- After the install is done, type the following lines in the terminal to ensure that these dependencies are in package-lock.json file.
  - npm install mysql2 
  - npm install sequelize 
  - npm install dotenv
- After installing the dependencies create a .env file where the DB_USER and DB_PASSWORD is your user name and password for mysql. Then create a .gitignore file to hide the .env from being seen by others if you are pushing to your repo.
- Next, enter mysql by typing **mysql -u ('your username') -p** to initialize mysql and then type source schema.sql; to easily target the ecommerce database.
- Lastly, run **npm run seed** to seed your database with information to fully utilize all of the RESTful routes

Click here to watch a video on the projects functionality: [here](https://drive.google.com/file/d/1hVQw-mzzEJvZHdx1Spv5n_blKuKhRBY2/view)

## Contact Info

- GitHub Repo: [Nephew20](https://github.com/Nephew20?tab=repositories)
- Email: cofieldk20@gmail.com
