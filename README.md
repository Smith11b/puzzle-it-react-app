## Getting started

1. Install [Node](https://nodejs.org/en/download/).
    - With homebrew: `brew install node`
2. Run `npm install` from root directory of this repo
3. Make sure to set the environment vairable `REACT_APP_BASE_URL` is set
    - You can to this by setting terminal env variable or through `.env` file
4. Run `npm start`

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

Some other testing options are:
- `npm run test:cov` This will run testing and generate code coverage report
- `npm run test:nowatch` This will run testing but will not start interactive watch 

### `npm run verify`

This is a convience command for running the `npm run lint` and `npm run test:cov`. Useful for pipelines.
<br>

- `npm run lint` This runs eslint and looks for code style issues and some potential bugs.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and getConfiguration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the getConfiguration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

