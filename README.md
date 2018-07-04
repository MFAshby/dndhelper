# Expo + firebase starter kit for Si

Ensure you have [node JS](https://nodejs.org/en/download/) installed.

Install [Expo](https://expo.io) (preferrably the [command line tool](https://docs.expo.io/versions/latest/introduction/installation.html))

Ensure you have [git](https://git-scm.com/download) installed.

Clone this repository using git 
```
git clone https://github.com/MFAshby/dndhelper.git
```

Run the expo tool and follow the instructions to open it on a phone

```
cd dndhelper 
exp start
```

I have added anonymous firebase authentication to the app, see *App.js*. This allows storing user data in firebase without requiring emails and passwords, and you have the option of converting to named accounts later. *HomeScreen.js* adds an indicator showing the firebase user id for now.

I have set up a firebase project *si-hambly-s-dnd-helper* where all the data can be stored (& you can see number of users etc.)

The different app pages are stored in *screens* so you can probably start there!

# Useful links
* [Codecademy](https://www.codecademy.com/learn/introduction-to-javascript) quick introduction to javascript. 
* [React Native](https://facebook.github.io/react-native/) Documentation and tutorials.
* [Expo](https://docs.expo.io/versions/latest/) Documentation
* [Firebase realtime database](https://firebase.google.com/docs/database/web/start) introduction and documentation. 