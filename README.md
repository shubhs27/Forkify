# Forkify

Forkify is a recipe web app that utilizes the Forkify API to allow users to search, view, modify, bookmark, and add their own recipes.

## Features
- **Search for recipes**
  - Input field to send requests to the API with searched keywords
  - Display search results with pagination
  - Show recipe details, including cooking time, servings, and ingredients

- **Update the number of servings**
  - Functionality to dynamically update all ingredient quantities based on the selected number of servings

- **Bookmark recipes**
  - Save favorite recipes for quick access
  - Display a list of all bookmarked recipes

- **Create custom recipes**
  - Users can upload their own recipes
  - Uploaded recipes are automatically bookmarked
  - User-created recipes are private and cannot be seen by other users

- **Persistent data storage**
  - Bookmarks and recipes are stored in the browser using local storage, allowing users to retain data even after leaving the app


## Built With
- **HTML**
- **CSS / SASS**
- **JavaScript (ES6+)**
- **Parcel (Module Bundler)**
- **Babel**
- **Forkify API**
- **Libraries**: `fractional`


## Project Architecture
- The app follows the **MVC (Model-View-Controller)** pattern.
- Modular JavaScript structure for maintainability and scalability.



## Getting Started

To get a local copy up and running, follow these steps:

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/shubhs27/Forkify.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Forkify
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm start
   ```

## Screenshots
![image](https://github.com/user-attachments/assets/398d1acc-bff6-48ac-966b-0d40e90f0fe3)





## Future Enhancements

1. **User Authentication & Profiles**
   - Implement user authentication so users can create accounts and save their bookmarked recipes across different devices.

2. **Advanced Filtering & Sorting**
   - Implement sorting options based on preparation time, popularity, or ingredient count.

3. **Ingredient-Based Recipe Suggestions**
   - Allow users to input ingredients they have and suggest recipes they can make.

4. **Shopping List Feature**
   - Enable users to generate a shopping list based on recipe ingredients.
   - Integrate with grocery APIs for real-time pricing and availability.

5. **Meal Planning & Calendar Integration**
   - Users can plan their meals for the week and add recipes to a calendar.
   - Option to export meal plans to Google Calendar.

6. **Dark Mode & UI Enhancements**
   - Add a dark mode toggle for better accessibility and aesthetics.
   - Improve UI with animations and better responsiveness.

7. **Offline Mode**
   - Cache recipes and bookmarks for offline access using service workers.

8. **Recipe Rating & Comments**
   - Allow users to rate recipes and leave comments or reviews.
   - Display average ratings for each recipe.




## Acknowledgments
- This project is part of Jonas Schmedtmann's Udemy course - The Complete JavaScript Course 2025: From Zero to Expert!
- All assets and UI components are inspired by the course material.

## License
This project is licensed under the MIT License.

---
Feel free to modify and enhance this project as needed!
