cmd f
"live code along"
any weekday ref
modals

# Live Code Along - Login & Sign up

0.Before you start this code-along, your code should be up to date with this code:

[Snap-Engineering-Academy-2021/chapsnat](https://github.com/Snap-Engineering-Academy-2021/chapsnat/tree/nav)

1. **First, before we begin, let's add some icons!**

```jsx
yarn add @expo/vector-icons
```

- By importing this package, you now have a ton of icons available at your fingertips here: [https://ionic.io/ionicons](https://ionic.io/ionicons)

```jsx
yarn add react-native-gesture-handler
```

- By importing this, you'll be able to use your app on mobile too!

1. **Next up, we're going to be adding a lot of new files. After this code-along in Part2, your code should look like this:** 
    
    [Snap-Engineering-Academy-2021/chapsnat](https://github.com/Snap-Engineering-Academy-2021/chapsnat/tree/login)
    
    Summary: 
    
    - App.js → New navigators
    - screens folder  → ProfileScreen, FriendsScreen, LoginScreen, SignupScreen (placeholders for now)
    - navigation folder → BottomTabNavigator.js
    - components folder → TabBarIcon.js component
    - constants folder → Colors.js file to keep track of colors for us

1. **Finally, we're going to create a functional Login/Signup! After this code-along in Part3, your code should look like this:** 
    
    [Snap-Engineering-Academy-2021/chapsnat](https://github.com/Snap-Engineering-Academy-2021/chapsnat/tree/login2)
    
    Summary: 
    
    - screens folder → LoginScreen
        - Try logging in with test@gmail.com, "abcdef"
    - Firebase authentication updates in the console
        
        <aside>
        💡 Username: chapsnatsea@gmail.com
        Password: snapacademies
        
        </aside>
        
    - screens folder → SignupScreen
    - If time permits, let's style the SignupScreen!