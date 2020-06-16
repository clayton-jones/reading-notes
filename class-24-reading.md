**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 24 Reading - Routing and Component Composition  

## Discussion Questions:  
  
1. **Why do we not need more .html pages in a multi-page React app?**  

    *The `react-router-dom` package gives us the ability to define which components are rendered based on the page URL. This means that instead of reloading an entire different page, `React` will replace the content on the page with new components that match the path.*  

2. **If we wanted a component to show up on every page, where would we put it and why?**  
    * Outside the `<BrowserRouter />`
    * Inside the `<BrowserRouter />`, outside a `<Route />`
    * Inside a `<Route />`

    *A component that needs to be displayed on every "page" such as a `nav` or `header` can be placed either outside of the `<BrowserRouter />` or inside it but outside the `<Route />` and it will still render on each page. The only time it will matter is if you are using `<Link />` inside any of those components. In that case it will beed to be placed inside of the `<BroswerRouter />` or `React` will throw an error.*  

3. **What does props.children contain?**  

    *`props.children` contains any content or components that was placed between the parent component tags.*

    *Example:*  
    ```HTML
    <Section>
      <p>Hello World</p>
    </Section>
    ```  
    The component:  
    ```JS
    export default function Section(props) {
      return (
        <div>
          {props.children}
        </div>
      )
    }
    ```



