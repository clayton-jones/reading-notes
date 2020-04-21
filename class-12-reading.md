**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 12 Reading - OAuth  

## Discussion Questions:  
  
1. **What’s a benefit of using OAuth instead of your own basic authentication?**  

    *OAuth allows an application to acquire additional information, like name, profile picture, email, etc without you having to provide it.*  

2. **Write the following steps in the correct order:**
  - Receive access token
  - Redirect to a third party authentication endpoint
  - Register your application to get a client_id and client_secret
  - Make a request to a third-party API endpoint
  - Ask the client if they want to sign in via a third party
  - Receive authroization code
  - Make a request to the access token endpoint  

    *1. Ask the client if they want to sign in via a third party*  
    *2. Redirect to a third party authentication endpoint*  
    *3. Register your application to get a client_id and client_secret*  
    *4. Make a request to a third-party API endpoint*  
    *5. Receive authroization code*  
    *6. Receive access token*  
    *7. Make a request to the access token endpoint*  

      
3. **What can you do with an authorization code?**  

    *An authorization code allows the server to read information on the user.* 

4. **What can you do with an access token?**  

    *The access token can be used in any future request for data, in place of going through the OAuth process again.*  


