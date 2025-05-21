# Next.js Taxi App

A modern, responsive taxi booking application built with Next.js, designed to provide a seamless user experience for both riders and drivers.

## Objectives

* Develop a user-friendly taxi booking platform using Next.js.
* Implement real-time location tracking and mapping features.
* Provide separate interfaces for riders and drivers.
* Ensure responsive design for optimal performance on both desktop and mobile devices.

## Technologies Used

* **Frontend**:

  * ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs\&logoColor=white) **Next.js**: A React framework for building server-side rendered applications.
  * ![React](https://img.shields.io/badge/React-61DAFB?logo=react\&logoColor=black) **React**: A JavaScript library for building user interfaces.
  * ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss\&logoColor=white) **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
  * ![Leaflet](https://img.shields.io/badge/Leaflet-3A8DFF?logo=leaflet\&logoColor=white) **Leaflet**: A JavaScript library for interactive maps.
  * ![Mapbox](https://img.shields.io/badge/Mapbox-000000?logo=mapbox\&logoColor=white) **Mapbox**: A mapping platform for custom maps and geolocation services.

* **Backend**:

  * **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine.
  * **Express.js**: A minimal and flexible Node.js web application framework.

* **Database**:

  * **MongoDB**: A NoSQL database for storing application data.

* **Authentication**:

  * **JWT (JSON Web Tokens)**: For secure user authentication and authorization.

## Features

* **User Authentication**: Secure login and registration system for both riders and drivers.
* **Real-time Location Tracking**: Track the user's location and display nearby available drivers.
* **Ride Booking**: Allow riders to book rides, view driver details, and track ride status.
* **Driver Dashboard**: Enable drivers to accept or reject ride requests, view trip details, and manage earnings.
* **Responsive Design**: Optimized for both desktop and mobile devices.
* **Admin Panel**: Manage users, drivers, and rides from a centralized dashboard.

## Applications

This application is ideal for:

* **Ride-hailing Services**: Providing a platform for users to book rides and drivers to accept requests.
* **Transportation Companies**: Managing a fleet of vehicles and drivers.
* **Developers**: Learning and implementing real-time location tracking and mapping features.

## Future Enhancements

To further enhance this project, consider implementing the following features:

* **Payment Integration**: Allow users to pay for rides through the application.
* **Rating and Reviews**: Enable riders and drivers to rate each other and provide feedback.
* **Push Notifications**: Notify users and drivers about ride status updates.
* **Ride History**: Maintain a history of past rides for users and drivers.
* **Advanced Search Filters**: Allow users to filter drivers based on vehicle type, rating, and other criteria.

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/SulemanMughal/nextjs-taxi-app.git
   cd nextjs-taxi-app
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   * Create a `.env.local` file in the root directory and add the following:

     ```
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     NEXTAUTH_URL=http://localhost:3000
     MAPBOX_ACCESS_TOKEN=your_mapbox_access_token
     ```
   * Replace `your_mongodb_connection_string` with your MongoDB connection string.
   * Replace `your_jwt_secret` with a secret key for JWT authentication.
   * Replace `your_mapbox_access_token` with your Mapbox access token.

4. **Run the development server**:

   ```bash
   npm run dev
   ```

5. **Access the application**:
   Open a browser and go to `http://localhost:3000/`.

## Contributing

Contributions are welcome! If you would like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.
