# The Recipe Hub: Recipe Management System

## 🔗 Live Project Link

## A complete end-to-end demonstration including all modules and functionality

[https://drive.google.com/file/d/1y-P5u5pyzFAvZT3YM1tGcadMoRIcISUq/view?usp=sharing](https://drive.google.com/file/d/16b1fcSdWyB3Wjhs61bK5mYLLJuL0DmTV/view?usp=sharing)


## Project Workflow / Video Demonstration

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [User Authentication (Login & Registration)](#2-user-authentication-login--registration)
- ["What to Cook?" - Category-Based Recipe Discovery](#3-what-to-cook---category-based-recipe-discovery)
- [Advanced Recipe Search & Filtering](#4-advanced-recipe-search--filtering)
- [Add Your Own Recipes](#5-add-your-own-recipes)
- [Contact Us](#6-contact-us)
- [Running the Project Locally](#running-the-project-locally)
- [Testing the Application](#testing-the-application)
- [Conclusion](#conclusion)


## Introduction

The Recipe Hub is a personalized recipe management system that allows users to register, create profiles, 
and discover recipes based on their dietary preferences, allergies, ingredient availability, and cooking 
habits. Users can search recipes by cuisine, meal type, or cooking time, and leave ratings and reviews on 
recipes they’ve tried. 
Originally built using Spring Boot and MySQL for the backend, the application uses HTML, CSS, and 
JavaScript for the frontend. Recipe data is fetched from a structured database with optional support for 
external APIs. Performance is enhanced with basic caching techniques, and the entire system is designed 

## Features

This project boasts a rich set of features to enhance the user experience:

### 1. Intuitive Navigation
![Mobile View - Hero Section and Search](https://raw.githubusercontent.com/Putta-Madhavi/recipeprojectimages/refs/heads/main/Screenshot%202025-06-30%20142354.png)

Upon opening the project, you'll be greeted with a clear and easy-to-navigate interface. The main sections accessible are:

* **Home:** The landing page providing an overview.
* **Recipes:** Where all the delicious recipes reside.
* **Add Recipes:** For users to contribute their own recipes.
* **Contact:** For any inquiries or feedback.

### 2. User Authentication (Login & Registration)
![](https://raw.githubusercontent.com/Putta-Madhavi/recipeprojectimages/refs/heads/main/Screenshot%202025-07-01%20153543.png)
Users can seamlessly manage their profiles and access personalized features through secure login and registration functionalities:

* **Registration:** Create a new account with details like full name, email, password, cooking skill level, dietary preferences, allergies, and ingredients to avoid.
* **Login:** Existing users can log in using their email and password.
* **Dashboard Integration:** After successful login, the user's name is displayed on the dashboard or website, providing a personalized experience.

### 3. "What to Cook?" - Category-Based Recipe Discovery
![](https://raw.githubusercontent.com/Putta-Madhavi/recipeprojectimages/refs/heads/main/Screenshot%202025-07-01%20152809.png)

 "What to Cook?" section allows users to explore recipes based on 10 distinct categories, making it easy to find exactly what you're craving. Categories include:

* All Types
* Quick & Easy Meals
* Vegetarian & Vegan Delights
* Healthy & Low-Carb Recipes
* Desserts & Sweets
* Breakfast & Brunch Specials
* Street Food & Snacks
* Main Courses & Dinner Ideas
* Soups, Salads & Sides
* Festive & Traditional Recipes

### 4. Advanced Recipe Search & Filtering
![](https://github.com/Putta-Madhavi/recipeprojectimages/blob/main/Screenshot%202025-07-01%20154011.png)
Find the perfect recipe with our powerful search and filtering options:

* **General Search:** Utilize the search bar to find recipes by keywords .
* **Filter by Cuisine Type:** Narrow down results by specific cuisines .
* **Filter by Meal Type:** Find recipes suitable for breakfast, lunch, dinner, or any other meal.
* **Filter by Cooking Time:** Specify a maximum cooking time to fit your schedule .
* **Dietary Requirements:** Easily filter recipes based on dietary needs such as vegetarian, vegan, gluten-free, etc.
* **Ingredient Preferences:** Refine your search based on specific ingredients you want to include or avoid .
* **View Complete Recipe:** Access detailed instructions and full ingredient lists for any selected recipe.
* **Rate Recipes:** Share your experience by rating recipes on a scale of 1 to 5 stars.
* **Send Reviews:** Leave comments or feedback on recipes to help other users.

### 5. Add Your Own Recipes
![](https://raw.githubusercontent.com/Putta-Madhavi/recipeprojectimages/refs/heads/main/Screenshot%202025-07-01%20154535.png)

Share your culinary expertise with the community! Our "Add Recipe" feature allows users to submit their own recipes with detailed information:

* Recipe Name
* Cuisine
* Meal Type
* Cooking Time (minutes)
* Category
* Ingredients (comma-separated)
* Step-by-step Instructions
* Nutritional Info 
* Average Rating 
* Recipe Image URL
 
### 6. Contact Us
![](https://raw.githubusercontent.com/Putta-Madhavi/recipeprojectimages/refs/heads/main/Screenshot%202025-07-01%20154735.png)

We value your feedback! The "Contact Us" section provides a straightforward form for users to get in touch with us for any questions, suggestions, or support:

* Full Name
* Email
* Subject
* Message
   
## Running the Project Locally

Follow these steps to set up and run the Recipe Hub on your local machine.

### Step 1: Prerequisites

Ensure you have the following installed:

* **Java JDK 17 or above**
* **Spring Boot Install**
* **MySQL server running** (with a database created for the project)
* **Code editor** 
* **Postman** 

### Step 2: Backend Setup (Spring Boot)

1.  **Create Database:**
    Open MySQL and create a database for the project.

2.  **Update `application.properties`:**
    Configure your database connection details in `src/main/resources/application.properties` within the backend project.

3.  **Run the Application:**
    Open the backend project in your IDE (e.g., IntelliJ IDEA, VS Code with Java extensions) and run the application.
    You can typically do this from your terminal within the backend project directory using:
    ```bash
    mvn spring-boot:run
    

4.  **Access Backend:**
    The backend APIs will be accessible at: `http://localhost:8080/`

### Step 3: Frontend Setup (HTML/CSS/JS)

1.  **Open the Frontend Folder in VS Code:**
    Navigate to the folder where your `index.html` file is located within VS Code.

2.  **Install Live Server Extension:**
    * Go to the **Extensions** tab in VS Code (Ctrl+Shift+X or Cmd+Shift+X).
    * Search for "Live Server" and click **Install**.

3.  **Run the Frontend Locally:**
    * Right-click on `index.html` in your VS Code explorer.
    * Select "Open with Live Server".
    * The site will open in your default browser.

### Step 4: Frontend-Backend Connection

Ensure your frontend API calls are directed to the correct backend endpoint. The frontend is configured to point to:
`http://localhost:8080/api/recipes`


## Testing the Application

* Test user registration, recipe submission, search, and reviews directly from the frontend user interface.
* Use Postman or your browser's developer tools to thoroughly test individual backend API endpoints and verify request/response cycles.

## Conclusion

The Recipe Hub is a complete recipe management system that demonstrates the seamless integration of a responsive frontend with a powerful Spring Boot backend and a MySQL database. It empowers users to register, personalize their experience, search for recipes, and contribute their own, making it a dynamic and user-centric platform for culinary enthusiasts.
