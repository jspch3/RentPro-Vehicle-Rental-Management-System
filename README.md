Vehicle Rental System - Rent Pro
A modern, full-featured web application for managing vehicle rentals. Built with React and Vite, this project provides a fast, responsive, and user-friendly interface for both customers and administrators. Users can browse vehicles, make bookings, and manage their accounts, while administrators have access to a dashboard for managing inventory, bookings, and generating reports.

✨ Key Features
User Authentication: Secure user registration and login functionality using JSON Web Tokens (JWT).

Dynamic Routing: A seamless single-page application (SPA) experience with protected routes for authenticated users, powered by React Router.

Vehicle Management: Full CRUD (Create, Read, Update, Delete) functionality for administrators to manage the vehicle fleet.

Booking System: Intuitive interface for users to browse available vehicles, select rental dates, and complete bookings.

PDF Generation: Capability to generate invoices or booking reports in PDF format using jsPDF and jsPDF-AutoTable.

Responsive UI: Modern and fully responsive user interface built with Tailwind CSS, ensuring a great experience on any device.

Iconography: Clean and modern icons from Lucide React and React Icons to enhance user experience.

🛠️ Tech Stack
This project is built using a modern and robust set of technologies:

Frontend Library: React

Build Tool: Vite

Styling: Tailwind CSS

Routing: React Router DOM

HTTP Client: Axios for making API requests.

Authentication: JWT-Decode for handling JWTs on the client-side.

PDF Generation: jsPDF & jsPDF-AutoTable

Icons: Lucide React & React Icons

Linting: ESLint for maintaining code quality.

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
Make sure you have Node.js (v18 or higher) and npm installed on your machine.

Installation
Clone the repository:

Bash

git clone https://github.com/your-username/vehiclerental.git
cd vehiclerental
Install NPM packages:

Bash

npm install
Set up environment variables: Create a .env.local file in the root of the project and add the necessary environment variables, such as the backend API URL.

VITE_API_BASE_URL=http://localhost:8080/api
Run the development server:

Bash

npm run dev
The application will be available at http://localhost:5173 (or the next available port).

📜 Available Scripts
In the project directory, you can run the following commands:

npm run dev: Runs the app in development mode with hot-reloading.

npm run build: Builds the app for production to the dist folder.

npm run lint: Lints the code using ESLint to check for errors and style issues.

npm run preview: Serves the production build locally to preview it before deployment.

🔧 Configuration
Vite (vite.config.js): The core configuration for the build tool, including the React and Tailwind CSS plugins.

ESLint (eslint.config.js): Contains the rules for code linting to ensure code consistency and quality.

Tailwind CSS (tailwind.config.js): Customize your design system, add custom animations, themes, or extend Tailwind's default utility classes here.

🤝 Contributing
Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
This project is not licensed. You can add a license file (e.g., LICENSE.md) to define how others can use, modify, and distribute your code. The MIT License is a popular choice for open-source projects.
