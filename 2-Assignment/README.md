# mcc2134-module4-navlisting
Integrate Navigation, Listing with Props, Hooks

Last module we learned about Navigation module and how to switch between screens

There are two ways to switch between screens. One is using props and the other is using the useNavigation hook.

Props are a good way to pass parameters to a component and allow those properties (props) to define how the component is to interact, looks, behave, etc.  

But there are different parts of an application that require ‘global’ control that would be difficult to pass around a property for the entire application

## Resources
https://dummyjson.com/docs/posts

## Seed the same id to make sure the same random image is shown with this url
item.image = 'https://picsum.photos/seed/' + item.id + '/600/600';



## React Navigation Libraries
npm install @react-navigation/native
expo install react-native-screens react-native-safe-area-context
npm install @react-navigation/native-stack