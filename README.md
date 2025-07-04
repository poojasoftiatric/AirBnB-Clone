# Airbnb Clone

## Overview

This repository contains a **full-stack clone of Airbnb**, built with the **MERN stack** — **MongoDB**, **Express.js**, **React.js**, and **Node.js**.  
The application replicates core Airbnb functionality, enabling users to search stays, view property details, book listings, and manage reservations.


## Getting Started

Follow these steps to set up the project on your local machine:

1. **Clone the Repository:**

   ```bash
   git clone origin https://github.com/poojasoftiatric/AirBnB-Clone.git

   ```

2. **Install dependencies:**

   Navigate to the client folder first and install the frontend packages:

   ```
   yarn install
   ```

   Next, navigate to the api folder and install backend packages:

   ```
   yarn install
   ```

3. **ENV variables:**

   - Add and update the .env file inside the client folder.

   - Add and update the .env file inside the api folder.

   - Fill in all required keys such as your database URI, JWT secret, Cloudinary keys, etc.


4. **Run project:**
   - Run the frontend:
     Open a terminal, switch to the client folder and start the dev server:
   ```
       yarn run dev
   ```
   - Run the backend:
     Open another terminal, switch to the api folder and start the server:
   ```
       yarn start
   ```

## Technologies Used

 - **MongoDB** – Flexible NoSQL database for listings and user data.
 - **Express.js** – Server-side framework for the REST API.
 - **React.js** – Frontend UI built with reusable components.
 - **Node.js** – Backend runtime for JavaScript.
 - **Tailwind CSS** – Utility-first CSS for styling.
 - **Shadcn** – UI kit built on Tailwind for faster development.
 - **JWT (JSON Web Tokens)** – Authentication and session handling.
 - **Cloudinary** – Cloud-based image storage and delivery.
 - **Google Cloud** – For Gmail-based OAuth sign-in.
