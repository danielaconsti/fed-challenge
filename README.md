# Challenge instructions

Using the API provided by [https://randomuser.me/](https://randomuser.me/), create a single page app for a user directory. 

This application should do the following:

- Display a paginated list of users (up to 10 users/page)
- For each user, display a card with the following information
  - First Name
  - Last Name
  - Email Address
  - Phone Number
  - Age
  - Gender
  - Picture

We've created an empty React project, which you can fork, as a starting point for the exercise. Besides React, you should not use any other UI frameworks to create the final application. The design of the application is ultimately up to you but should display nicely in multiple viewports.

We review the exercise on the following topics:

- Code Quality
- Organization
- UI / UX
- Complexity
- Attention to Detail
- Nice to Haves (accessibility and documentation)

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

#### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

#### `yarn storybook` 

It will start Storybook locally and output the address. Depending on your system configuration, it will automatically open the address in a new browser tab and you'll be greeted by a welcome screen.
