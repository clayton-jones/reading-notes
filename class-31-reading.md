**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 31 Reading - Redux: Combined Reducers 

## Vocab:

### Combined Reducers
* Pulling in multiple reducers and creating keyed objects from them

### `combineReducers()`
* function imported from redux, used to combine multiple reducers
* this effectively creates a "super reducer" containing all reducers you give it
* multiple reducers can respond to the same action