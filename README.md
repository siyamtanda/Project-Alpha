# Project Alpha - Backend

## Description

This is the backend server for Project Square, an application created as part of the Full Stack Developer Challenge by Accenture. The backend is responsible for serving data to the React front-end and includes endpoints for retrieving, sorting, and filtering trusted brands.

## Features

- Provides a RESTful API for the trusted brands section.
- Retrieves, sorts, and filters brand data.
- Connects to a MongoDB database for data storage.
- Handles various HTTP requests from the React app.

## Project Structure

The backend server is structured as follows:

- `app.js`: Main application file with Express configuration.
- `models/`: Contains the MongoDB schema and models.
- `routes/`: Includes route handlers for different API endpoints.
- `README.md`: This documentation file.

## Getting Started

To run the backend server locally, follow these steps:

1. **Clone the Repository**

   ```bash
   https://github.com/siyamtanda/Project-Alpha.git


1.N **Navigate to the Backend Directory**

cd Project-Alpha/server

**Install dependencies**

npm install express mongoose cors nodemon axios

**Start the Backend Server**

- npm run dev

The backend server will start and run on the specified port (e.g., 3001).

## API Endpoints

- GET /brands: Retrieve all trusted brands.
- GET /brands/sort: Retrieve brands sorted alphabetically.
- GET /brands/filter: Filter brands by name.
- GET /visa: Define a route for Visa API data (you can implement your own logic).

## Contributing

If you'd like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them.
- Push your changes to your fork.
- Create a pull request to the original repository.
  
## License

This project is licensed under the Siyamtanda License.

**Copyright © 2023 Accenture. All rights reserved.**



