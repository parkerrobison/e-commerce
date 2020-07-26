# E-commerce Back End

  ![licensebadge](https://img.shields.io/badge/license-Apache-blue)

  ## Description 
  
  This project has set up the back end portion of a mock e-commerce site. The database contains information about categories, products, and tags in the form of tables. The technologies used to create this database are MySQL2, sequelize, and express.js API. Additionally, the dotenv package was used to store sensitive data as environment variables. This application has no front end, so all of the API endpoints are tested using Insomnia. From the API endpoints, a user can manipulate the database tables by creating, reading, updating and deleting data to manage inventory and keep it up to date. 
  
  
  ## Table of Contents
  
  * [Installation](#installation)
  * [Usage](#usage)
  * [Credits](#credits)
  * [License](#license)
  

  ## Installation
  
  All dependencies should be included in the project. Simply clone the repository from github to your local repository.
  
  ## Usage 

  1) Clone the repository to your local repository. 
  2) Go to the connection.js page and on line 7 replace the process.env variables replace those with the database name, the MySQL username, and the MySQL, in that order. 
  3) Go to the root folder of the local repository in the terminal. 
  4) Connect to MySQL by typing in 'mysql -u root -p' 
  5) Enter the password. 
  6) Connect to the ecommerce_db using source db/schema.sql. 
  7) Exit the MySQL shell 
  8) Seed the database by typing 'npm run seed' in the command line. 
  9) Run the program by typing in 'npm start' 
  10) Open and use insomnia to test the routes on localhost after connecting to the server.
   
  ## License

  Apache

  ## Questions
  If you run into any errors or have further questions about this program, you can contact here: 
  *github: https://github.com/parkerrobison 
  *email: parkerobison@gmail.com.
  Please reference the project in question in the message. Thank you.
