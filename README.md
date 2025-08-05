# Food Delivery Project

=======================

## Overview

---

This is a food delivery project built using NestJS as the backend framework and React Native as the frontend framework. The project allows users to browse and order food from various restaurants, and also provides features for restaurants to manage their menus and orders.

### Features

- **User authentication and authorization**
- **Restaurant management** (create, read, update, delete)
- **Menu management** (create, read, update, delete)
- **Order management** (create, read, update, delete)
- **Payment processing using Stripe**
- **Real-time updates using WebSockets**

## Technologies Used

---

- **NestJS** (Backend Framework)
- **React Native** (Frontend Framework)
- **PostgreSQL** (Database)
- **Stripe** (Payment Gateway)
- **WebSockets** (Real-time updates)

## Project Structure

---

The project is divided into two main folders: `server` and `client`.

### Server

- `server`: This folder contains the NestJS backend code, including the API endpoints, database models, and services.

### Client

- `client`: This folder contains the React Native frontend code, including the app components, navigation, and services.

## Installation

---

To install the project, follow these steps:

1. **Clone the repository** using `git clone`.
2. **Install the dependencies** using `npm install` or `yarn install`.
3. **Create a new PostgreSQL database** and update the `DATABASE_URL` environment variable in the [server/.env](cci:7://file:///c:/Users/user/Documents/_PROJECTS/_PET/react-native-food-delivery/server/.env:0:0-0:0) file.
4. **Start the server** using `npm run start` or `yarn start`.
5. **Start the client** using `npm run start` or `yarn start` in the `client` folder.

## API Documentation

---

The API documentation is generated using Swagger and can be accessed at `http://localhost:3000/api/docs`.

## Contributing

---

Contributions are welcome! Please submit a pull request with a clear description of the changes made.

## License

---

This project is licensed under the MIT License. See the `LICENSE` file for details.
