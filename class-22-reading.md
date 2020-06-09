**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 22 Reading - React Testing and Deployment  

## Discussion Questions:  
  
1. **Describe a case where snapshot testing would be useful, and describe another case where it would be ineffective.**  

    *Snapshot testing is useful when you are refactoring a "finished" page, and want to make sure the layout remains unchanged. It is not very useful, however, when you are continually restructuring your UI, as it will then fail when the layout is changed.*  

2. **What is the difference between full mount and shallow mount?**  

    *A full mount renders and allows the testing of a component and any child components, while a shallow mount only renders the current component.*  

3. **What does npm run build do?**  

    *`npm run build` optimizes React code for development and creates a "seemingly static" webpage ready for deployment.* 



