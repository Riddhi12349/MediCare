# MediCare (HealthCare Support Platform)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
<br>

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Introduction

The **Medi-Connect (Appointment Booking System)** is a comprehensive web-based solution designed to streamline hospital operations by implementing efficient queuing models for Outpatient Departments (OPDs), real-time bed availability tracking, patient admission management, and inventory management for medicines and consumables. This system is scalable and can be integrated with a city-wide module, facilitating seamless coordination across multiple healthcare institutions.

Developed for the Smart India Hackathon, this platform aims to enhance patient experience, optimize hospital resources, and improve overall healthcare delivery in urban settings.

<br>

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">


## Features

### 1. Secure Data Storage and Sharing
- Role-based access control implemented using **JWT (JSON Web Tokens)**.
- Ensures only authorized users (patients, doctors, and medical staff) can access or share sensitive medical data.
- Safeguards medical prescriptions, reports, and patient details, maintaining data privacy.

### 2. Real-time Chat System
- **Real-time communication** built for seamless interaction among patients, doctors, and staff.
- Enables users to share important updates and support discussions within the community.

### 3. QR Code Scanning for Quick Record Access
- Integrated **QR code scanning** functionality for fast and easy access to patient records.
- Allows quick scanning and retrieval of patient details, streamlining the medical data lookup process.

### 4. Responsive UI with ReactJS and Material-UI
- **ReactJS** and **Material-UI** were used to create responsive and user-friendly interfaces.
- Ensures a smooth user experience on devices of all sizes, including desktops, tablets, and mobile devices.

### 5. Efficient State Management with Redux
- **Redux** was implemented to manage the application's state efficiently.
- Ensures consistent state updates, improves application performance, and enhances maintainability.

## Technologies Used
- **Frontend**: ReactJS, Material-UI
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **State Management**: Redux
- **Authentication**: JWT (JSON Web Tokens)
- **Real-time Communication**: Socket.io
- **QR Code Scanning**: QR Code library

<br>

<!--Line-->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Tech Stack

- **Frontend**

  - [React.js](https://reactjs.org/)
  - [Redux](https://redux.js.org/) (for state management)
  - [React Router](https://reactrouter.com/)
  - [Axios](https://axios-http.com/) (for API calls)
  - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) / [SASS](https://sass-lang.com/)

- **Backend**

  - [Node.js](https://nodejs.org/)
  - [Express.js](https://expressjs.com/)
  - [MongoDB](https://www.mongodb.com/) (or PostgreSQL/MySQL)
  - RESTful APIs
  - [JWT](https://jwt.io/) for authentication

- **Deployment**

  - [Render](https://www.render.com/)
  - [Netlify](https://www.netlify.com/)

- **Other Tools**
  - [Git](https://git-scm.com/) & [GitHub](https://github.com/)
  - [Postman](https://www.postman.com/) (for API testing)
  - [ESLint](https://eslint.org/) & [Prettier](https://prettier.io/) (for code quality)

<br>

## Getting Started

Follow these instructions to set up a local copy of the repository on your machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)
- [MongoDB](https://www.mongodb.com/) (if using MongoDB as the database)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Riddhi12349/MediCare
   cd medi-connect
   ```

2. **Install Backend Dependencies**

   ```bash
   cd server
   npm install
   ```

3. **Install Frontend Dependencies**

   ```bash
   cd client
   npm install
   ```

4. **Backend Configuration**

- Open the `.env` file and update the following variables:

```env
PORT=5000
PASSDB=your_mongodb_connection_string
JWT=your_jwt_secret
```
