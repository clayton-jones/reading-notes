**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 07 Reading - Express

## Discussion Questions:  
  
1. **What code does the server actually run?**  

    *An express server doesn't actually run anything while it's on, but instead waits for requests.*  

2. **What Express/HTTP operations map to CRUD operations?**  

    *POST, GET, PUT, DELETE*  

3. **What does res.send() do?**  

    *Send is a method that formats and sends information to the client.*  

4. **What is the order of operations for the three categories of middleware (handler, application, route)?**  

    *Application -> Route -> Handler*  

5. **What is the parameter next used for?**  

    *It calls the next middleware in the application.*