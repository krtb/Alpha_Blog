# Alpha Blog

Basic blog demponstrating use of rails CRUD operations

## Creating a route
1) create route path in `routes.rb`
   1) add an action, `welcom#home`
2) create controller in `app/controllers`
   1) inherit from `ApplicationController`
3) Add action/method, like `#home`
4) Add View in `views`
   1) add file as .html.erb

## Naming Conventions
* Model Name - `Article`
  * Singular
  * First letter UPPERCASE
* Table Name
  * Plural
  * lowercase of model name
* Model File Name - `article.rb`
  * SINGULAR
  * all lowercase 
* Controller Name - `articles_conrtoller.rb`
  * plural of model