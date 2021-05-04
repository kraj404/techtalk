I have developed recipe management app. Main features of the web site
  - Search recipe using Phrase like Pasta dishes or with ingredients
  - It will display key information and nutritional information about recepe
  - Site uses external recipe API to provide search results in addition to recipe created in the site
  - Also site provides user management
  -   New user can registered to site to add recepies as favorites
  -   User can add reviews to recepies
  -   Home page provides random recipe and Food Fact
  -   Users can create brand new recipe if they do not find recipe they are looking
  -   User can see all their favorite recipes and their own recipes in Favorites page
  

Techncial Stack
- Python3 , Postgress SQL, SQLAlchemy, Jinga, CSS, JavaScript, JQuery, Bootstrap, REST APIs

Search results and Recipe details used to display data from two sources
- Spoonacular recipe API
- Postgress SQL data (Content created in the site is stored here)

In the recipe details page content is deplayed based on recipe requested in the local database or coming from external data source.
When recipe details are displayed it indicates if the recipe is part of user favorites and if they have added any reviews for the recipe

