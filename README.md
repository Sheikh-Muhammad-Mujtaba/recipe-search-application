# Recipe Search App

## About the App
The **Recipe Search App** is a user-friendly web application that allows you to find delicious recipes by searching for ingredients. Whether you're looking to cook a quick meal with what's available at home or exploring new dishes, this app will provide you with a variety of recipe options based on your input. You can search for popular dishes or experiment with different ingredients.

## Key Features
- **Ingredient Search:** Enter ingredients you have on hand to discover matching recipes.
- **Popular Suggestions:** Explore popular recipes like Biryani, Chicken Karahi, and more with just one click.
- **Recipe Details:** View detailed information such as preparation time, calorie count, and ingredient list.
- **Responsive Design:** The app is fully responsive and adapts to different screen sizes.
- **Dark Mode Toggle:** Switch between light and dark themes for a more personalized experience.
- **Loading Animation:** A sleek loading spinner gives visual feedback during data fetching.
- **Quick Links:** Click on any recipe to view the full instructions on the source website.

## Tech Stack Used
- **Next.js:** A powerful React framework for building optimized, server-rendered web apps.
- **React:** A JavaScript library for creating interactive UIs.
- **ShadCN UI Components:** Pre-built UI components integrated with Tailwind CSS for a consistent design system.
- **Tailwind CSS:** Utility-first CSS framework to style components quickly and efficiently.
- **TypeScript:** Provides type safety for predictable code.
- **Lucide-React:** Icon set to visually enhance the user interface.
- **ClipLoader:** Simple loading spinner used while fetching recipes.
- **Edamam API:** External API used to fetch recipe data based on ingredients or dish names.

## How It Works
1. **Search Recipes by Ingredients:**
   - Enter ingredients (or dishes) you want to search for in the search bar and click the search button.
   - The app makes an API call to the Edamam API using the entered query to fetch matching recipes.

2. **Explore Popular Recipes:**
   - Click on any of the suggested popular recipes like Biryani or Nihari to quickly search for those dishes.

3. **View Recipes:**
   - The results will display as recipe cards with an image, title, preparation time, and calorie count.
   - Click on any recipe card to be redirected to the full recipe on the source website.

4. **Dark Mode:**
   - Toggle between dark and light mode using the button in the header for a personalized experience.
