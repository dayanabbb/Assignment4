# Book Store

## Introduction
This web app is a book store, containing information about the books from our local store and global library book list.

## Installation
1. Clone the repository
2. Run `npm install` to install dependencies
3. Run `nodemon app.js` to start the server
4. Open your browser and go to http://localhost:3000

## Dependencies
-axios: allows making HTTP requests to endpoints and handling responses asynchronously;
-bcrypt: used for securely storing passwords in databases by hashing them before storage and comparing hashed passwords during authentication;
-body-parser: allows parsing various types of request bodies, such as JSON, URL-encoded, and raw;
-dotenv: used in Node.js applications to manage environment-specific configurations;
-ejs: simplifies the process of generating HTML dynamically based on data from the server;
-express: simplifies the process of handling HTTP requests, routing, middleware integration, and more;
-express-session: provides session management capabilities, such as session creation, storage, and retrieval, using various session stores;
-google-translate-api: allows interacting with the Google Translate service to translate text between languages programmatically;
-i18n: a library for internationalization and localization in Node.js applications. It provides utilities for managing translations, formatting dates, numbers, currencies, and other locale-specific data;
-mongoose: provides a schema-based solution for modeling application data, defining schemas, performing CRUD operations, and enforcing data validation.

## Server
The server runs on port 3000.

## API's used
Google Books API - API provided by Google that allows developers to access a wealth of information about books and related content.

## Usage
1.Log in or sign in.
2.If you are signing in, you can not write the role, it will be assigned as a "user" automatically.
3.If you log in as a user, you can see the catalog of books and take the quiz. Click the "quiz" button on the navigation bar and take the quiz. The results will be above the questions.
4.As an admin you can add, update, delete books; delete users by their email.

## Admin page
To log in as an admin 
Email: dayana@gmail.com
Password: 123abc


