# E-Commerce Server Side Database

## Description

The E-Commerce program develops the backend needed to store and manipulate inventory data for an e-commerce site.  The database contains the products that has a product name, price, stock and category id; the categories with the category name; and the tags with tag names.  The products have a one to many relationship with categories and many to many relationship with tags.  All three tables have endpoints created to read the data (all or by unique id), create new data, update existing data, or delete data.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)

## Installation

In order to run the program, you can download or clone the program from my GitHub site. In the root directory of the program, ensure all packages are available by typing 'npm init' and 'npm install' in the command line. You will also have to MySQL which can be downloaded at [https://dev.mysql.com/downloads/mysql/](https://dev.mysql.com/downloads/mysql/) and create a file named .env with the following two lines:<br />
DB_USER='your-mysql-username'<br />
DB_PW='your-mysql-password'<br />
If you want to use template data, you can seed the tables with npm run seed.  Then the program should be available to execute with "node server.js" or "npm start".  

## Usage

The e-commerce back end program can be used to implement CRUD methods to an inventory for a e-commerce site. A video of how the program operates and testing through Insomnia Core can be seen [here](https://drive.google.com/file/d/1Fhs_aSaBLd660T4aO3yF6qxePXR_z8RG/view).

Screenshot showing Insomnia Core output for retrieving products:<br />
![Products Screenshot](/img/Screenshot-products.png "E-Commerce Product Results")

Screenshot showing Insomnia Core output for retrieving categories:<br />
![Categories Screenshot](/img/Screenshot-categories.png "E-Commerce Category Results")

Screenshot showing Insomnia Core output for retrieving tags:<br />
![Tags Screenshot](/img/Screenshot-tags.png "E-Commerce Tag Results")


## Questions

The E-Commerce Database can be found on the following [GitHub page](https://github.com/kunkelkevin/e-commerce).<br />If you have any additional questions, you can email me at [kunkelkevin@yahoo.com](mailto:kunkelkevin@yahoo.com)


