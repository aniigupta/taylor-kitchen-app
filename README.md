# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Here’s an updated version of the **README** file based on your latest requirements:

---

# Recipe Finder Application

This project helps busy professionals like **Taylor** quickly find recipes based on the ingredients they have at home. The app uses **TheMealDB API** to suggest recipes that can be made with those ingredients, making meal planning easier and faster.

## Features

- **Search Recipes by Ingredients**: Enter ingredients you have available, and the app will suggest recipes that can be made with those ingredients.

## Tech Stack

- **Frontend**: React.js
- **API**: TheMealDB API - A free API providing information about meals and recipes based on ingredients.
- **Styling**: Styled-components (for React component styling)

## Installation

To get started with this project, follow the steps below:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/recipe-finder.git
cd recipe-finder
```

### 2. Install Dependencies

Install the necessary dependencies using npm or yarn:

```bash
npm install
# OR
yarn install
```

### 3. Set Up API

The app relies on **TheMealDB API** to fetch recipes. No API key is required for this project.

### 4. Start the Development Server

Run the application in development mode:

```bash
npm start
# OR
yarn start
```

The app will be running on [http://localhost:3000](http://localhost:3000).

## Usage

Once the application is running, you can:

- **Enter Ingredients**: Type in the ingredients you have (e.g., chicken, tomatoes, etc.) and click the search button to view relevant recipes.

## API Reference

The app uses **TheMealDB API** for fetching meal data. Here's the API endpoint you will interact with:

### Endpoint: `https://www.themealdb.com/api/json/v1/1/filter.php?i={ingredient}`

Replace `{ingredient}` with the ingredient you want to search for (e.g., `chicken`, `tomato`, `beef`).

## Future Enhancements

- **User Authentication**: Allow users to save their favorite recipes for easy access.
- **Meal Planning**: Add a feature to create weekly meal plans based on the user's ingredients.
- **Recipe Rating and Comments**: Enable users to rate and review recipes.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. We welcome improvements, bug fixes, and suggestions for new features!

## License

This project is open-source and available under the [MIT License](LICENSE).

---

### Notes for Taylor (User Persona)

This app is designed with you in mind! As a busy professional, you can quickly find recipes based on the ingredients you have at home. No more wasting time searching for meals—let the app do the work for you!

---

This version excludes the mood-based, time-based, and ingredient exclusion features and assumes you are only using the frontend with **TheMealDB API**.
