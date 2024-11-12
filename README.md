# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3002) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

#

# Meal Finder App

A React-based web application to search and view meal recipes by category or meal name. This app allows users to browse meals from different categories, search for specific meals, and view detailed instructions for each recipe.

## Features

- **Meal Search:** Users can search for meals by name.
- **Category Listing:** Users can browse meals by category.
- **Meal Details:** View detailed information about each meal including ingredients and instructions.
- **Responsive Design:** The app is fully responsive and works well on both desktop and mobile devices.
- **Loading State:** A shimmer effect is shown while the meal data is being fetched.

## Tech Stack

- **Frontend:** React.js
- **State Management:** React useState and useEffect hooks
- **Routing:** React Router for handling routing between pages
- **Icons:** Material-UI icons (Home icon)
- **API:** Fetch data from a public meal API to display meal details and categories.

## Folder Structure

- recipe
  - Node_modules
  - Public
  - src
    - api
      - api.js
    - Components
      - Category.js
      - CategoryInfo.js
      - Header.js
      - MainPage.js
      - MealInfo.js
      - Mealscard.js
      - Search.js
      - SimmerEffect.js
    - app.js
    - Index.css
    - gitignore
    - index.js
    - README.md
    - package.json
    - package-lock.json
    - tailwind.config.js

## Setup and Installation

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (Version 14 or higher)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Steps to Run the Project

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/bankarbhushanps://github.com/your-username/meal-finder-app.git
   cd meal-finder-app
   ```
