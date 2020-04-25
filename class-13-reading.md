**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 13 Reading - Bearer Authorization  

## Discussion Questions:  
  
1. **When is Basic Authorization used vs. Bearer Authorization?**  

    *Bearer authentication is used when sending a token that represents a user, where basic authorization is used when sending a username & password?*  

2. **What does the JSON Web Token package do?**  

    *The JWT package creates a token to be used in place of having the user sign in with their username and password each time.*  

3. **What considerations should we make when creating and storing a SECRET?**  

    *The SECRET should remain... secret. It allows for the decryption of the JWT and therefore should not be made public. Maybe store it in the environment variables.* 


