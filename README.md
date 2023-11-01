# Worldwise

Welcome to Worldwise, a comprehensive web application designed to provide users with a rich interactive experience exploring global cities and their various attributes. Built with modern web technologies, Worldwise aims to deliver a seamless and informative journey through the world's geography.

## Features

- **Interactive Map**: Explore a dynamic map that allows you to view cities across the globe.
- **City Information**: Get detailed insights into city demographics, weather, and other key statistics.
- **Country List**: Browse a list of countries and their associated cities within the application.
- **User Authentication**: Secure login functionality to ensure a personalized experience.
- **Responsive Design**: Enjoy a fully responsive web design that adapts to various screen sizes and devices.
- **Geolocation Hook**: Utilize geolocation features to find cities near you.

## Technologies

Worldwise is built using the following technologies:

- **React**: A JavaScript library for building user interfaces.
- **Vite**: A modern frontend build tool that significantly improves the development experience.
- **Context API**: Leveraged for state management across the application.
- **Custom Hooks**: Implemented to encapsulate component logic and enhance reusability.

## Project Structure

The project is structured as follows:

- `src/`: Contains all the source code for the application.
  - `components/`: Reusable React components like `AppNav`, `City`, `CountryList`, etc.
  - `contexts/`: React context definitions for global state management.
  - `hooks/`: Custom React hooks, such as `useGeolocation`.
  - `pages/`: Page components that represent different views within the application.
- `data/`: Includes JSON data files like `cities.json` for the application's data layer.
- `vite.config.js`: Configuration file for the Vite build tool.

## Getting Started

To get started with Worldwise:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the dependencies with `npm install`.
4. Start the development server with `npm run dev`.
