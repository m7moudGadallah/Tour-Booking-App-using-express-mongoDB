# Tour Booking APP Using Express & MongoDB

A full-stack application for booking tours that combines a RESTful API and server-side rendering using Node.js, Express, and MongoDB.

## Table of content

<!-- TOC -->

- [Tour Booking APP Using Express & MongoDB](#tour-booking-app-using-express--mongodb)
    - [Table of content](#table-of-content)
    - [Introduction](#introduction)
    - [key Features](#key-features)
    - [Technologies](#technologies)
    - [Getting Started](#getting-started)
        - [Prerequisites](#prerequisites)
        - [Installation](#installation)
    - [Testing](#testing)
        - [Running Tests](#running-tests)
        - [Test Coverage](#test-coverage)
    - [Designs and Documentation](#designs-and-documentation)
    - [License](#license)

<!-- /TOC -->

## Introduction

Welcome to the Tour Booking App! This project provides both a RESTful API for programmatic access and server-side rendering using Pug for a seamless user experience. It is built using Express.js, Node.js, and MongoDB as the database. This application for users who want to book tours, leave reviews, and interact with the platform, as well as administrators and lead tour guides who need specialized dashboards for management.

> 💡Note: This project is currently a work in progress.

**[&uarr; Top](#tour-booking-app-using-express--mongodb)**

## key Features

- **Authentication & Authorization:** Secure user authentication and authorization system.
- **Exploring Tours (client):** Users can browse and search for available tours.
- **Booking Tours (client):** Users can book tours they are interested in.
- **Rating and Reviewing Tours:** Clients can leave reviews and ratings for tours they've booked.
- **Payment for Booked Tours:** Integration with Stripe for secure payment processing.
- **Admin Dashboard:** A powerful admin dashboard for managing tours, bookings, reviews, and users.
- **Lead-Tour-Guide Dashboard:** Specialized dashboard for lead tour guides displaying their tours and relevant statistics.

**[&uarr; Top](#tour-booking-app-using-express--mongodb)**

## Technologies

- Node.js
- Express.js
- MongoDB (Database)
- Mongoose (ODM)
- Pug (for server-side rendering)
- JWT (JSON Web Tokens)
- Stripe (for payments)
- Jest (for unit and integration testing)
- Supertest (for testing HTTP endpoints)

**[&uarr; Top](#tour-booking-app-using-express--mongodb)**

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed.
- MongoDB installed and running.
- Git installed (if you plan to clone the repository).

**[&uarr; Top](#tour-booking-app-using-express--mongodb)**

### Installation

1. Clone the repository:

   > git clone https://github.com/m7moudGadallah/Tour-Booking-App-using-express-mongoDB.git

2. Navigate to the project directory:

   > cd app

3. Install the project dependencies:

   > npm install

4. Rename `.env.env` to `.env` and set the actual values for your environment variables in the .env file.

5. Start the application in development mode:

   > npm run start:dev

The application should now be accessible at `http://localhost:3000`.

6. To run the application in production mode, use:

   > npm run start:prod

**[&uarr; Top](#tour-booking-app-using-express--mongodb)**

## Testing

We ensure the reliability of this application through unit and integration testing using `Jest` and `Supertest`.

### Running Tests

1. Ensure that you have installed all project dependencies, including development dependencies:

   > npm install

2. Run the unit and integration tests:
   > npm test

### Test Coverage

We maintain a high level of code coverage to ensure that our application functions correctly and securely. You can view the test coverage report by running:

> npm run test:coverage

The coverage report will be available in the coverage directory.

**[&uarr; Top](#tour-booking-app-using-express--mongodb)**

## Designs and Documentation

Designs and documentation for this project can be found in the **_[docs](./docs/)_** directory.

**[&uarr; Top](#tour-booking-app-using-express--mongodb)**

## License

This project is licensed under the MIT License - see the **_[LICENSE](./LICENSE)_** file for details.

**[&uarr; Top](#tour-booking-app-using-express--mongodb)**
