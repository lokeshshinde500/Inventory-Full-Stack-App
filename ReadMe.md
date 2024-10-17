sorry my backend folder is not opening in github plz refer this repo 

backend repo link : https://github.com/lokeshshinde500/Inventory-App-Backend

Inventory Management API

Frontend Deployment : https://legendary-baklava-3925d3.netlify.app

Backend Deployment : https://inventory-app-backend-zma5.onrender.com

This is a RESTful API built with Express.js for managing inventory items. It supports CRUD operations as well as bulk operations for importing and exporting inventory data using CSV files.

Table of Contents

Installation
Usage
API Endpoints
Installation

inventory-management-api

Install dependencies:

npm install
Set up your environment variables. Create a .env file and configure your database connection and any other necessary settings.

Start the server:

npm start
npm run dev

Usage
You can use tools like Postman or curl to interact with the API. The server runs on http://localhost:3000 by default.

API Endpoints

Normal CRUD Operations

Create New Inventory

POST /
Get All Inventories

GET /
Get a Single Inventory by ID

GET /:id/single
Update Inventory by ID

PATCH /:id
Delete Inventory by ID

DELETE /:id
Bulk Operations for CSV
Import CSV

POST /import (Ensure to send the file with the upload middleware)
Export CSV
GET /export

Dependencies

This project uses the following npm packages:

cors: ^2.8.5 - Middleware for enabling CORS (Cross-Origin Resource Sharing).
csvtojson: ^2.0.10 - Library to convert CSV data to JSON format.
dotenv: ^16.4.5 - Module for loading environment variables from a .env file.
express: ^4.21.1 - Web framework for building the API.
json2csv: ^6.0.0-alpha.2 - Library to convert JSON data to CSV format.
mongodb: ^6.9.0 - MongoDB driver for Node.js.
mongoose: ^8.7.1 - ODM (Object Data Modeling) library for MongoDB and Node.js.
multer: ^1.4.5-lts.1 - Middleware for handling multipart/form-data, used for file uploads.




