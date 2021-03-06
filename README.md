# React-Native-Boilerplate

Complete starter kit for react-native projects.

## (Wix) React-Native-Navigation

You can access the starterkit builded with react-native-navigation via this link:

[React-Native-Navigation](https://github.com/IbrahimCanKALYA/starterkit)

## Description

This repository created for initilazing react-native apps fast as we can and keep our focus on the coding. Project includes the requirements for almost all react-native projects. Also i used markdown files for petite descriptions of components and screens. Throughout the project i used yarn and i encourage you to use yarn. React-Native version: 0.59.10

## Libraries

Libraries installed to project :

- > react-navigation : 3.11.1
- > react-native-firebase : 5.5.5
- > redux : 4.0.1
- > react-redux : 7.1.0
- > redux-saga : 1.0.3
- > redux-persist : 5.10.0
- > redux-logger : 3.0.6
- > react-native-swiper : 1.5.14
- > react-native-keyboard-aware-scroll-view : 0.8.0

## Setup

You don't need to do spesific installation or configuration. Change project name to your project and follow instructions for firebase.

## Firebase Installation

>**Android**

- Put your google-services.json under android/app/

>**iOS**

- Put your GoogleService-Info.plist under ios/[YOUR_PROJECT_NAME]/

## Coding Style

Project configurated coding with Airbnb standarts and **Eslint** - **Prettier** installed and configured.
Also project configurated coding with static type checking with flow. **Flow** installed and configurated for using this coding styles please follow the editor configuration instractions.

## Editor Instructions

**1** .Add this extensions to your editor

```js
ESLint// For writing code according to Airbnb standarts...
Prettier-Code formatter// Fixes many mistakes according to Eslint Airbnb standart for our project...
Flow Language Support// Support us to static type checking with react-native...
markdownlint// Linter for .md descriptions which is written inside of the project...
```

**2**. Add following lines to your editor workspace settings for prettier, flow and eslint work.(**If you are using vscode skip this step because workspace setting for vscode included inside of the repository**)

```js

  // Format a file on save. A formatter must be available, the file must not be auto-saved, and editor must not be shutting down.
  "editor.formatOnSave": true,
  // Support using flow through your node_modules folder, WARNING: Checking this box is a security risk. When you open a project we will immediately run code contained within it.
  "flow.useNPMPackagedFlow": true,
  // Enable/disable JavaScript validation. (For Flow)
  "javascript.validate.enable": false,
  // Enable/disable default JavaScript formatter (For Prettier)
  "javascript.format.enable": false,
  // Use 'prettier-eslint' instead of 'prettier'. Other settings will only be fallbacks in case they could not be inferred from eslint rules.
  "prettier.eslintIntegration": true
```

## Scripts

- yarn android-clean-run : this script cleans android build and re-builds the app.


## ToDo

- [x] Android Support
- [x] iOS Support
- [x] Adding simple Jest test
- [x] Adding markdown descriptions to components and screens
- [ ] Cucumber scenario & Appium test for login scenario
- [ ] react-native-firebase notificaton utility functions

## License

[MIT](https://opensource.org/licenses/mit-license.html)
