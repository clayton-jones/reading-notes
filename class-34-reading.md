**[Back](https://clayton-jones.github.io/reading-notes/)**

# Class 34 Reading - React Native  

## Links
### [Getting Started with React Native](https://reactnative.dev/docs/getting-started)  
### [React Native Basics (Tutorial)](https://reactnative.dev/docs/tutorial)  
### [React Native Docs](https://reactnative.dev/)  
### [Expo](https://expo.io/)  
### [Expo Snack](https://snack.expo.io/)  
### [Ejecting](https://docs.expo.io/expokit/eject/?redirected)  

---------------

React Native is an intuitive way to create mobile apps using the React framework (but not).  
### Pros: 
- Those familiar with React will be able to hit the ground running, with minimal challenges/alterations.  

- Saves time: You can develope one code base (with some differing files for Android/iOS) and have it work on multiple OS.
### Cons:
- Performance: React Native runs slower than natively developed applications. If performance is your top priority, shell out the time ( and $$$) for a native dev (or two).

- Security: While React Native has some security packages available to use, the built-in encryption from a native OS is superior. If you are handling sensitive data, open up your wallets and get a native dev or two.

Here is a small snippet of basic React Native code:

```JS
import React from 'react';
import { Text, View } from 'react-native';

const YourApp = () => {
  return (
    <View style={{ flex: 1, justifyContent: "center", alignItems: "center" }}>
      <Text>
        Sample Text
      </Text>
    </View>
  );
}

export default YourApp;
```