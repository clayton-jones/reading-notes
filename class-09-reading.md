**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 09 Reading - API Server

## Discussion Questions:  
  
1. **Describe a use-case where param middleware would come in handy.**  

    *Param middleware is used whenever a specific param exists in the request. It is useful for validating the key-value pair before proceeding to the route.*  

2. **What are the two ways to add middleware in-between Mongoose and MongoDB interactions?**  

    *Adding a join by reference and a virtual join.*  

3. **What is the difference between a join by reference and a virtual join?**  

    *A join by reference directly relates the key values of two objects, and a virtual join lets you store the actual key, vs storing the ObjectId* 

4. **What do localField and foreignField mean?**  

    *It looks like the localField refers to the key of the products object, and the foreignField refers to the key of the localField. Maybe.*  
