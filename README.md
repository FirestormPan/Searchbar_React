# A React Searchbar demo
A React application that demonstrates client-side search and filtering of a simple dataset using reusable components.

You can search through a catalogue of "Spaceships" with filters of text input(name) and/or by object properties(engine, location). The filtering is done in the front end, by javascript functions.  Each spaceship card component has a star button that allows the user to save <i>spaceships</i> (objects) in a different component. This allows multiple searches under different criteria, showcasing simple state/context managment.
<br>Responsive design with Bootstrap. New rows are added (or removed) dynamically, according to the number of "spaceship components" that need to be rendered.

# How To Run
After downloading the files, run __npm install__ in the root folder. Then run __npm start__

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
