# Car API

This is a simple RESTful API for managing a list of cars.

## Table of Contents

- [Endpoints](#endpoints)
  - [Get All Cars](#get-all-cars)
  - [Add a New Car](#add-a-new-car)
  - [Update a Car](#update-a-car)
  - [Delete a Car](#delete-a-car)
- [Testing with Postman](#testing-with-postman)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Endpoints

### Get All Cars

- **URL**: `http://localhost:8080/api`
- **Method**: `GET`
- **Response**: Returns an array of car objects.

### Add a New Car

- **URL**: http://localhost:8080/api
- **Method**: POST
- **Response**: Returns the added car object.

### Update a Car

- **URL**: http://localhost:8080/api/:id (replace :id with the car ID)
- **Method**: PUT
- **Response**: Returns the updated car object.

### Delete a Car

- **URL**: http://localhost:8080/api/:id (replace :id with the car ID)
- **Method**: DELETE
- **Response**: Confirmation message.

### Testing with Postman

- **GET All Cars**: Set request type to GET and use URL http://localhost:8080/api. Click Send.
- **Add a New Car**: Set request type to POST, use URL http://localhost:8080/api, select raw body as JSON, and provide the new car object. Click Send.
- **Update a Car**: Set request type to PUT, use URL http://localhost:8080/api/:id, select raw body as JSON, and provide updated car details. Click Send.
- **Delete a Car**: Set request type to DELETE, use URL http://localhost:8080/api/:id. Click Send.

### Installation:

Clone the repository:
git clone https://github.com/01Newbie/car-api
Navigate to the project directory: cd car-api
Install the dependencies: npm install
Start the server: node server.js
Open Postman to test the API.

### Contributing

If you'd like to contribute, please fork the repository and create a pull request.

### License

This project is licensed under the MIT License.
