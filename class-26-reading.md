**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 26 Reading - Hooks API  

## Discussion Questions:  
  
1. **What does a component’s lifecycle refer to?**  

    *A component's lifecycle refers to how long it is "alive" and maintaining information in an application.*  

2. **Why are functional components preferred over class components?**  

    *Functional components are preferred for their simplicity.*  

3. **What is wrong with the following code?**  

```JS
import React, {useState, useEffect} from 'react'; 
   
function MyComponent(props) {
  const [count, setCount] = useState(0); 
     
  function changeCount(e) {
    setCount(e.target.value); 
  }
     
  let renderedItems = []
     
  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update'); 
    }, [count]); 
       
    renderedItems.push(<div key={i}>Item</div>); 
  }
     
  return (<div>
    	<input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}
```

  *Hooks should not be used within loops, but instead at the highest level of the component.*




