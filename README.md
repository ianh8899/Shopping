# Clothing Store App

Welcome to the Clothing Store App! This application is built using React, Strapi, Stripe, and SASS. Here, you'll find the necessary instructions to set up and run the application.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Setting up Environment Variables](#setting-up-environment-variables)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- **React**: Used for building the user interface of our clothing store.
- **Strapi**: Backend CMS for managing and serving content.
- **Stripe**: Facilitates secure payments for the clothing store items.
- **SASS**: Preprocessor scripting language that is interpreted or compiled into CSS.

## Installation
1. Clone the repository from GitHub:
   \
   git clone "https://github.com/ianh8899/Clothing-Store-App"
   \
2. Navigate to the `api` folder and install the necessary packages:
   \
   cd api
   npm install
   \
3. Once that's done, navigate to the `client` folder and install the necessary packages:
   \
   cd ../client
   npm install
   \

## Usage
1. Start the Strapi backend:
   \
   cd api
   npm run develop
   \
2. Open a new terminal window and start the React frontend:
   \
   cd client
   npm run dev


Your app should now be running! Visit your browser and head to port "localhost:5173" to view the Clothing Store App.
Access the strapi backend on "localhost:1337/admin"

Your app should now be running! Visit your browser and head to port `localhost:5173` to view the Clothing Store App. Access the Strapi backend on `localhost:1337/admin`.

## Setting up Environment Variables
For the app to function correctly, certain environment variables need to be set. Both the `api` and `client` directories have `.env.example.env` files which provide templates for setting up your environment variables.

1. In the `api` directory, copy the `.env.example.env` to a new file named `.env`:
   ```bash
   cd api
   cp .env.example.env .env


  Then, edit the `.env` file with your preferred text editor and populate the required values.

2. Similarly, in the `client` directory:
   ```bash
   cd api
   cp .env.example.env .env

 Then edit the `.env` file with your preferred text editor and populate the necessary values.

## Technologies Used
- [React](https://reactjs.org/)
- [Strapi](https://strapi.io/)
- [Stripe](https://stripe.com/)
- [SASS](https://sass-lang.com/)

