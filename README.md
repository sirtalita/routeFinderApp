# Route Finder: - A REACT APPLICATION

## Overview: 
Implementing route finding algorithms: Dikstra’s algorithm and A* algorithm.

This app is entirely built in react

I used two algorithms to solve thge problem.

### Dijkstra
- Dijkstra's Algorithm lets us prioritize which paths to explore. Instead of exploring all possible paths equally, it favors lower cost paths.
- We can assign lower cost to encourage moving on roads while assigning high cost on highway to avoid them.
- It is the algorithm of choice for finding the shortest path paths with multiple destinations.

### A* (A-Star)
- A* is a modification of Dijkstra's Algorithm that is optimized for a single destination.
- Dijkstra's Algorithm can find paths to all locations; A* finds paths to one location. It prioritizes paths that seem to be leading closer to a goal.

------------------
## Getting Started ..
First install node.js which comes with a bundle(npm+npx) to run javascript in local system.
type following commands in the shell to create a react app

```
clone the project
cd my-app
npm install
```

### npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.
The page will reload if you make edits.
You will also see any lint errors in the console.



This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


## Deployment

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

----------------------------



## For more documentation and understanding.. check out following links..


You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
