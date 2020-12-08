In this activity, we will begin by installing a few helpful packages and then explore the React documentation to answer questions.

## Instructions

### Part 1

* Begin by executing Create React App by running the following command in your terminal:

`npx create-react-app <appname>` where `<appname>` is what you want to name your app. Example: `npx create-react-app practiceapp`.

# Hello React

In this activity, we will dissect a simple React application.

## Instructions

* If you haven't already, generate a starter React app using Create React App. You can do this by running `npx create-react-app reactpractice`. We will run all of the activity code today inside of this boilerplate, as to avoid constantly reinstalling the same node modules.

* Once you have a `reactpractice` React app generated, delete the `src` folder inside of your starter app and replace it with the [src](Unsolved/src) provided with this activity.

* Start the app by running `npm start` in your terminal, take a moment to study the HTML code being rendered in the browser at [http://localhost:3000](http://localhost:3000).

### HelloReact.js

* Then go into the `src` folder and with your partner, try to answer the following questions:

  * What's happening inside of `src/components/HelloReact.js`? How does it relate to the content being rendered to the browser?

### App.js

* Open the `src/App.js` file, what's going on in this file? Try to answer the following questions:

  * What does the `App` function return?

  * Why do we import the React library? We aren't using the React keyword anywhere. Is it possible to remove this and still have our code work?

### index.js

* Open the `src/index.js` file and go over the code. Notice that we're importing the `ReactDOM` library. Try to answer the following questions:

  * Do you remember what the purpose of `ReactDOM.render` is? What is it doing?

  * Is this where our components are rendered to the DOM?

  * Instead of splitting our files up into `App`, `components/HelloReact` and `index`, is it possible to just write our entire Hello World app in the `index.js` file?

### Part 2

* While those are installing, work with your group to answer each of the following questions using the [ReactJS Documentation](https://facebook.github.io/react/):

1. In the previous section we executed Create React App. What is it for?

2. What are some benefits of using ReactJS?

3. What is a React component? Hint: Check the "Components and Props" section of the React documentation.

4. What is the significance of the `ReactDOM.render` method? Hint: Check the "ReactDOM" section of the documentation.

5. What is JSX? Why does Facebook recommend using it? Hint: Check the "Introducing JSX" section of the documentation.

6. What does Facebook recommend as the “best way to start building a new React single page application”? Hint: Check the "Installation" section of the React documentation.

7. What is Babel? And what role does it play in converting JSX into vanilla JavaScript? Hint: Check the "Introducing JSX" section of the documentation.

8. What is the significance of { } curly braces in JSX? Hint: Check the "Introducing JSX" section of the documentation.

9. What is a component prop? Hint: Check the "Components and Props" section of the React documentation.
