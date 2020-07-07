**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 29 Reading - Redux  

## Discussion Questions:  
  
1. **Why would you wrap your entire application within a context?**  

    *Then you don't need to worry about which components have access to what context. It's all there.*  

2. **What is the purpose of a reducer?**  

    *A reducer is a function that updates the state of the redux application*  

3. **What does an action contain?**  

    *An action contains some data that you want to update the application with.* 

4. **Why do we need to copy the state in a reducer?**  

    *You cannot modify the state directly in a reducer, so you have to copy it, modify that copy, then return the updated copy.*  


