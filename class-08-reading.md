**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 08 Reading - Express Routing

## Discussion Questions:  
  
1. **What is a benefit to using express.Router()?**  

    *It allows you to modularize your routes so that everything is more organized and easier to manage.*  

2. **When I say that top-down order matters in Express, what does that mean?**  

    *An express server processes the routes and middleware from the top down, so you can determine the order that middleware or routes run.*  

3. **Why do we use a model class (with create(), read(), etc.) instead of directly calling MongoDB operations (such as save(), find(), etc.) within our Express route handlers?**  

    *Using a model class standardizes the CRUD operations, and allows it to be used on multiple applications.*  
