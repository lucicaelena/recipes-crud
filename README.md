# Recipes-crud

This app should be able to store recipes, to read recipes that you just added, edit and delete them.

Recipes-crud is a Flask-based CRUD (Create, Read, Update, Delete) application designed to manage recipes. 


This app is written in Flask.

`pip install Flask`

and it uses SQLALCHEMY as ORM.

`pip install flasq_sqlalchemy`


## Features

- **Create Recipe**: Users can add new recipes by providing details such as name, description, preparation time, and ingredients.
- **Read Recipe**: Users can view existing recipes, including all their details and ingredients. Recipes are paginated to improve browsing experience.
- **Update Recipe**: Users can modify the details of a recipe, such as its name, description, preparation time, or ingredients list.
- **Delete Recipe**: Users can permanently remove recipes from the database.
- **Search Recipes**: Users can search for recipes by name, displaying matching results.
- **Export Recipes**: Users can export recipes to a CSV file for further analysis or sharing.


## Installation

1. Clone this repository:

    ```
    git clone <repository-url>
    ```

2. Install dependencies:

    ```
    pip install Flask Flask-SQLAlchemy Flask-Migrate
    ```

3. Set up the database:

    ```
    flask db upgrade
    ```

4. Run the application:

    ```
    flask run
    ```

    







