**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 33 Reading - Redux: Additional Topics

It looks like the Redux Toolkit is condensing all of your store reducers and actions into one easy to declare bundle, so that it is easier to manage.

```javascript

const postsSlice = createSlice({ name: ‘posts’, initialState: [], reducers: { createPost(state, action) {}, updatePost(state, action) {}, deletePost(state, action) {} } })

// Extract the action creators object and the reducer const { actions, reducer } = postsSlice // Extract and export each action creator by name export const { createPost, updatePost, deletePost } = actions // Export the reducer, either as a default or named export export default reducer

// ————— Sample Use ————– //  

console.log(createPost({ id: 123, title: ‘Hello World’ }))  

// {type : “posts/createPost”, payload : {id : 123, title : “Hello World”}}

// Notice how createSlice transforms your defiition? console.log(postsSlice) /* { name: ‘posts’, actions : { createPost, updatePost, deletePost, }, reducer } */
```