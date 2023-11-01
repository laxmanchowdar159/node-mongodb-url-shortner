# node-mongodb-url-shortner
# URL Shortener Project

## Introduction

Welcome to the URL Shortener Project! This project is designed to provide a simple and efficient solution for shortening long URLs and tracking user interactions. It uses Node.js, Express, MongoDB, and Mongoose to achieve these functionalities.

## Technologies Used

- Node.js
- Express
- MongoDB
- Mongoose
- EJS (Embedded JavaScript)

## Project Overview

The URL Shortener Project is divided into several parts, each building upon the previous one:

1. **Setting up the Express server**: In this part, we initialize the Node server using Express, creating basic routes for handling incoming requests.

2. **Setting up our view engine**: We introduce the EJS template engine to render dynamic content, allowing users to interact with the application through the front-end.

3. **Setting up MongoDB**: Here, we establish a connection to the MongoDB database using Mongoose, ensuring structured data storage and retrieval.

4. **Setting up a Mongoose schema**: We define the data schema for our URL shortener, making it easy to manage and validate URL data.

5. **Linking the frontend, backend, + MongoDB**: This part connects the front-end and back-end, enabling users to submit URLs for shortening.

6. **Displaying short URLs on the frontend**: We fetch and display shortened URLs on the front-end, giving users easy access to their shortened links.

7. **Making the redirection work**: Finally, we make URL redirection functional while tracking click counts.

## Installation

Follow these steps to set up the project on your local machine:

1. Clone the repository: `git clone https://github.com/yourusername/url-shortener-project.git`
2. Change to the project directory: `cd url-shortener-project`
3. Install dependencies: `npm install`
4. Configure your MongoDB connection in the `index.js` file.
5. Start the server: `npm start`
6. Open a web browser and navigate to `http://localhost:YOUR_PORT`, where `YOUR_PORT` is the port on which the server is running.

## Usage

1. Access the web application using the provided URL.
2. Enter a long URL in the input field and click the "Shrink This!" button to obtain a shortened URL.
3. The application will display both the full URL and the shortened URL.
4. Clicking the shortened URL will redirect you to the original URL while incrementing the click count.

Feel free to extend the project as needed.

