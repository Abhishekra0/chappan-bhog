# 🍳 Recipe Hub - A Dynamic Recipe Website Frontend

Recipe Hub is the frontend for a visually appealing and interactive web application designed for browsing, searching, and adding culinary recipes. The design focuses on a clean, user-friendly, card-based interface with engaging animations to create a delightful user experience.

## ✨ Features

  * **🏡 Homepage**: Displays a responsive grid of recipe cards for easy browsing.
  * **🔍 Search Functionality**: A prominent search bar allows users to quickly find specific recipes.
  * **➕ Add New Recipes**: A dedicated page with a clean form for users to submit their own recipes.
  * **📄 Detailed Recipe View**: A separate page to display the full details of a selected recipe, including its image, ingredients, and instructions.
  * **🎨 Interactive UI & Animations**:
      * Smooth hover effects that scale up the recipe cards.
      * An elegant, animated heading that drops into view.
      * A gently animated background that transitions between warm, inviting colors.

## 🛠️ Technologies & Design

This project is built using standard web technologies and focuses heavily on modern CSS for its look and feel.

  * **HTML5**: Provides the basic structure for the web pages.
  * **CSS3**: Handles all styling, layout, and animations.
      * **CSS Flexbox & Grid**: Used to create responsive layouts for the main containers and the recipe card gallery.
      * **CSS Keyframe Animations**: Implemented for the dynamic background color transitions and the "drop-down" heading effect.
  * **Google Fonts**: The project uses the stylish 'Dancing Script' font for headings to give the site a unique personality.

## 📂 Project Structure

The CSS implies a simple multi-page structure. A typical file organization would be:

```
/project-root
├── index.html         # Main page with the recipe grid
├── add-recipe.html    # Page with the form to add a new recipe
├── recipe-details.html# Template page for a single recipe view
└── style.css          # The stylesheet containing all the provided styles
```

## 🚀 Getting Started

To run this project locally, follow these simple steps:

1.  **Create the files**: Create the HTML files (`index.html`, `add-recipe.html`, etc.) and the `style.css` file in a project folder.

2.  **Add the stylesheet**: Link the `style.css` file in the `<head>` section of all your HTML files:

    ```html
    <link rel="stylesheet" href="style.css">
    ```

3.  **Add Google Fonts**: To use the 'Dancing Script' font, add the following link to the `<head>` of your HTML files:

    ```html
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
    ```

4.  **Launch the website**: Open the `index.html` file in your favorite web browser.

## 🎨 Customization

You can easily customize the look and feel of the website by modifying the `style.css` file.

  * **Colors**: Change the background and theme colors by modifying the CSS variables or the properties in the `@keyframes colorChange` rule.
  * **Fonts**: Update the `font-family` properties in the `.animated-heading` or `body` styles to use different fonts.
  * **Animations**: Adjust the timing and effects of the animations by changing the values in the `@keyframes` rules.
