# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Recipe Finder Application

This project is designed to help users like **Taylor**, a busy professional, easily find recipes based on their available ingredients, cooking preferences, and time constraints. The application uses **TheMealDB API** to suggest recipes that match the user's needs, making it easier to plan meals and cook delicious dishes with minimal effort.

## Features

- **Search Recipes by Ingredients**: Users can search for recipes by entering the ingredients they have available at home. The app will suggest recipes that can be made with those ingredients.
- **Mood-Based Search**: Based on what the user feels like eating, the app can suggest different types of meals (e.g., vegan, vegetarian, dessert).
- **Time-Based Search**: Users can input the time they have for cooking, and the app will suggest quick meals or recipes that fit within the time constraint.
- **Exclusion of Ingredients**: The app allows users to filter out certain ingredients they do not want to include in their recipes, catering to dietary preferences or restrictions.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js (optional, if required for API handling)
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

The app relies on TheMealDB API to fetch recipes. No API key is required for this project.

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
- **Filter by Mood**: Use mood-based filters like "Vegetarian", "Dessert", or "Quick" to narrow down recipe suggestions.
- **Exclude Ingredients**: If there are ingredients you do not want to use, you can filter them out of the results.
- **Set Cooking Time**: Specify how much time you have, and the app will suggest recipes that can be made in that time frame.

## API Reference

The app uses **TheMealDB API** for fetching meal data. Here's the API endpoint you will interact with:

### Endpoint: `https://www.themealdb.com/api/json/v1/1/filter.php?i={ingredient}`

Replace `{ingredient}` with the ingredient you want to search for (e.g., `chicken`, `tomato`, `beef`).

## Future Enhancements

- **User Authentication**: Allow users to save their favorite recipes and preferences for a more personalized experience.
- **Meal Planning**: Add a feature to create weekly meal plans based on the user's preferences and ingredient availability.
- **Recipe Rating and Comments**: Enable users to rate recipes and leave feedback.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. We welcome improvements, bug fixes, and suggestions for new features!

## License

This project is open-source and available under the [MIT License](LICENSE).

---

### Notes for Taylor (User Persona)

This app is designed with you in mind! As a busy professional, you can quickly find recipes based on the ingredients you have at home or your current mood and time constraints. No more wasting time searching for meals—let the app do the work for you!
