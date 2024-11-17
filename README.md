# E-Commerce-Project

### Description
This project involves building the back end of an e-commerce site using the latest technologies. The application uses Express.js for the server, Sequelize as the ORM, and PostgreSQL as the database. It provides a functional API for managing product categories, tags, and inventory.

The back end supports CRUD operations and is tested using Insomnia Core.

### Table of Contents
Installation
Usage
Walkthrough Video
Features
API Routes
Technologies Used
License
Questions

### Installation
Clone the repository:
bash
Copy code
git clone <repository-url>
Install dependencies:
bash
Copy code
npm install
Set up your environment variables:
Create a .env file in the root directory and add your PostgreSQL credentials:
plaintext
Copy code
DB_NAME=ecommerce_db
DB_USER=<your_postgresql_username>
DB_PASSWORD=<your_postgresql_password>
Create and seed the database:
bash
Copy code
npm run schema
npm run seed
Usage
Start the server:
bash
Copy code
npm start
Test the API routes using Insomnia Core or another API testing tool:
Use GET, POST, PUT, and DELETE routes to manage categories, products, and tags.

### Walkthrough Video
Link to the walkthrough video

The video demonstrates the following: https://drive.google.com/file/d/13V5clE4z3gbEMtWKtRbisAbmGQ5RcmeT/view?usp=sharing

Setting up environment variables.
Creating and seeding the database.
Starting the server.
Testing API routes (GET, POST, PUT, DELETE) using Insomnia Core.
Features
Seamless Database Integration: Connects to a PostgreSQL database using Sequelize.
CRUD Operations:
Categories: Create, Read, Update, Delete.
Products: Create, Read, Update, Delete.
Tags: Create, Read, Update, Delete.
API Testing: Fully functional API routes tested using Insomnia Core.
Data Models:
Categories
Products
Tags
Product-Tags (junction table for many-to-many relationships)

### API Routes
Categories
GET /api/categories – Get all categories.
GET /api/categories/:id – Get a category by ID.
POST /api/categories – Create a new category.
PUT /api/categories/:id – Update a category by ID.
DELETE /api/categories/:id – Delete a category by ID.
Products
GET /api/products – Get all products.
GET /api/products/:id – Get a product by ID.
POST /api/products – Create a new product.
PUT /api/products/:id – Update a product by ID.
DELETE /api/products/:id – Delete a product by ID.
Tags
GET /api/tags – Get all tags.
GET /api/tags/:id – Get a tag by ID.
POST /api/tags – Create a new tag.
PUT /api/tags/:id – Update a tag by ID.
DELETE /api/tags/:id – Delete a tag by ID.

### Technologies Used
Node.js
Express.js
Sequelize
PostgreSQL
dotenv (for environment variables)

### Credit 
Tutor Joem C. and homework help with TA, Diem Ly

### License
This project is licensed under the MIT License.
