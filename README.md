# Meals Web App

<img src="screenshots/app_logo.png" alt="Meals Web App Logo" width="100"/>

## Overview
Meals Web App is a comprehensive recipe discovery platform that allows users to explore, filter, and save recipes based on various criteria including meal categories, complexity, and dietary preferences. With detailed recipe information and a responsive design, this web application provides a seamless culinary exploration experience across all devices.

## Features

### Recipe Discovery
- **Multi-criteria Filtering**: Filter recipes by:
  - Meal categories (breakfast, lunch, dinner, dessert, etc.)
  - Complexity level (simple, challenging, complex)
  - Affordability (budget-friendly, moderate, pricey)
  - Preparation time (quick, moderate, time-consuming)
  - Dietary preferences (vegetarian, vegan, gluten-free, lactose-free)
- **Search Functionality**: Find specific recipes by name or ingredients
- **Category Browsing**: Explore recipes within specific categories
- **Popular Recipes**: View trending and most-saved recipes

### Recipe Details
- **Comprehensive Information**: Detailed view for each recipe including:
  - Ingredients list with measurements
  - Step-by-step preparation instructions
  - Cooking time and difficulty level
  - Servings information
  - Nutritional information (calories, macronutrients)
- **Visual Guidance**: High-quality images for each recipe
- **Serving Adjustments**: Dynamically adjust ingredient quantities based on serving size

### User Experience
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Intuitive Navigation**: Easy-to-use interface with logical information hierarchy
- **Favorites System**: Save preferred recipes for quick access
- **Dark/Light Themes**: Customizable visual experience
- **Print-friendly Formatting**: Optimized recipe views for printing

### Additional Features
- **Meal Planning**: Create weekly meal plans using saved recipes
- **Grocery Lists**: Generate shopping lists from selected recipes
- **Rating System**: User ratings and reviews for recipes
- **Social Sharing**: Share favorite recipes on social media platforms
- **Related Recipes**: Suggestions for similar or complementary dishes

## Technologies Used
- **React.js**: Frontend framework for component-based UI
- **CSS3/SCSS**: Advanced styling with responsive design
- **Context API**: State management across the application
- **Custom Hooks**: Specialized functionality for recipe manipulation
- **Local Storage**: Persistent favorites and user preferences

## Screenshots

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <img src="screenshots/home_page.png" alt="Home Page" width="300"/>
    <img src="screenshots/category_view.png" alt="Category View" width="300"/>
    <img src="screenshots/recipe_details.png" alt="Recipe Details" width="300"/>
    <img src="screenshots/filter_interface.png" alt="Filter Interface" width="300"/>
    <img src="screenshots/favorites_page.png" alt="Favorites Page" width="300"/>
</div>

## Project Structure
```
src/
├── components/
│   ├── Layout/
│   │   ├── Header.js
│   │   └── Footer.js
│   ├── Meals/
│   │   ├── MealItem.js
│   │   ├── MealsList.js
│   │   └── MealDetail.js
│   ├── Categories/
│   │   ├── CategoryItem.js
│   │   └── CategoriesList.js
│   └── UI/
│       ├── Card.js
│       ├── Modal.js
│       └── Button.js
├── pages/
│   ├── HomePage.js
│   ├── CategoriesPage.js
│   ├── MealDetailPage.js
│   └── FavoritesPage.js
├── store/
│   ├── favorites-context.js
│   └── filters-context.js
├── hooks/
│   ├── use-http.js
│   └── use-filter.js
├── models/
│   ├── meal.js
│   └── category.js
└── utils/
    └── helpers.js
```

## Access
https://jiteshh-10.github.io/meals-web/


## Data Structure
The application uses the following data structure for recipes:

```javascript
{
  id: 'm1',
  title: 'Spaghetti with Tomato Sauce',
  affordability: 'affordable',
  complexity: 'simple',
  imageUrl: 'https://example.com/spaghetti.jpg',
  duration: 20,
  ingredients: [
    '4 Tomatoes',
    '1 Tablespoon of Olive Oil',
    '1 Onion',
    '250g Spaghetti',
    'Spices',
    'Cheese (optional)'
  ],
  steps: [
    'Cut the tomatoes and the onion into small pieces.',
    'Boil some water - add salt to it once it boils.',
    'Put the spaghetti into the boiling water - they should be done in about 10 to 12 minutes.',
    'In the meantime, heat up some olive oil and add the cut onion.',
    'After 2 minutes, add the tomato pieces, salt, pepper and other spices.',
    'The sauce will be done once the spaghetti are.',
    'Feel free to add some cheese on top of the finished dish.'
  ],
  isGlutenFree: false,
  isVegan: true,
  isVegetarian: true,
  isLactoseFree: true
}
```

## Future Enhancements
- User accounts with personalized recipe collections
- AI-powered recipe recommendations
- Video tutorials for complex recipes
- Ingredient substitution suggestions
- Seasonal recipe highlights
- Calorie and nutritional goal tracking

## Contribution
Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/jiteshh-10/meals-web/issues) if you want to contribute.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

