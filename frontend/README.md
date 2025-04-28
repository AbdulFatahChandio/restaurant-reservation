# 🍽️ AFC Food - Restaurant Website

[![GitHub issues](https://img.shields.io/github/issues/your-username/your-repo-name)](https://github.com/your-username/your-repo-name/issues)  
[![GitHub forks](https://img.shields.io/github/forks/your-username/your-repo-name)](https://github.com/your-username/your-repo-name/network)  
[![GitHub stars](https://img.shields.io/github/stars/your-username/your-repo-name)](https://github.com/your-username/your-repo-name/stargazers)  
[![GitHub license](https://img.shields.io/github/license/your-username/your-repo-name)](https://github.com/your-username/your-repo-name/blob/main/LICENSE)

A modern, fully responsive restaurant website built with **React.js** for the frontend and **Node.js** for the backend.  
This web application features smooth scrolling, a dynamic menu section, an introduction to the restaurant's team, and a clean, aesthetic user interface, making it an excellent example of a restaurant's online presence.

---

## 🚀 Features
- 🍴 **Smooth Scrolling Navigation:** Between sections like menu, team, and popular dishes.
- 📜 **Dynamic Menu Display:** Fetches data from a JSON file (or backend API) to display restaurant menu items.
- 📱 **Responsive Design:** Looks great on mobile, tablet, and desktop devices.
- 🍔 **Hamburger Menu for Mobile:** Easy-to-use navigation on small screens.
- 👨‍🍳 **Team Section:** Showcases the restaurant's talented staff and team members.
- 🔄 **Organized Code Structure:** Modular and easy to maintain.
- 🎨 **Aesthetic UI:** Clean and modern design focused on user experience.

---

## 🛠️ Technologies Used
- **Frontend:** React.js, React-Scroll, React-Icons, CSS3
- **Backend:** Node.js, Express.js
- **Version Control:** Git, GitHub
- **Development Tools:** Visual Studio Code, Postman for API testing

---

## 📂 Project Structure
/frontend |-- /components # React components for various sections of the website |-- Navbar.js # Navbar component with smooth scrolling and menu |-- Menu.js # Dynamic menu display component |-- Team.js # Team section showing staff members |-- PopularDishes.js # Popular dishes display component |-- Footer.js # Footer component with contact info and social links |-- /pages # React pages for routing |-- Home.js # Main landing page of the website |-- MenuPage.js # Page for displaying the menu |-- AboutUs.js # About section showing the restaurant's story |-- /assets # Images, icons, and static files used in the project |-- logo.png # Restaurant logo |-- dish1.jpg # Image of a popular dish |-- dish2.jpg # Image of another popular dish |-- App.js # Main React component that renders the app and routes |-- index.js # Entry point of the React app, renders App.js |-- /styles # CSS styles and themes |-- main.css # Main global styles |-- navbar.css # Styles specific to the Navbar |-- menu.css # Styles for the menu page /backend |-- /routes # Express routes for handling API requests |-- menuRoutes.js # Routes for fetching menu items from the server |-- teamRoutes.js # Routes for fetching team data |-- /controllers # Logic to handle data fetching and manipulation |-- menuController.js # Controller for menu data |-- teamController.js # Controller for team data |-- server.js # Main server setup file, initializes the Express app /restApi.json # Sample data for the menu and team (used for static content or testing) /README.md # Project documentation /LICENSE # License file (MIT or any other license you choose) .gitignore # Gitignore file to exclude unwanted files like node_modules /package.json # NPM dependencies and scripts /package-lock.json # Exact version of dependencies installed



- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
