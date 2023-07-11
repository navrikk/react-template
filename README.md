# react-template
A starter template React.JS project built using `create-react-app` that includes a static code analyzer,
 a code formatter, and a CSS framework. This project uses `yarn` as a package manager.

### Included libraries

- eslint
- prettier
- tailwindcss

### Steps to use this template project

- Clone this repo & rename the folder
- Delete the `.git` folder in the repo to remove the entire template git history
- Find and Replace all occurrences of `react-template`
- Replace the name in `<title>` tag in `public/index.html` with your app name
- Replace the strings & icons in `public/manifest.json` with ones specific to your app

#### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

#### `yarn lint`

Shows lint warnings and errors enforced by `eslint`

#### `yarn lint:fix`

Auto fixes every rule violation `eslint` is capable of repairing and prints out any warnings or errors it
 was incapable of fixing

#### `yarn format`

Formats files based on the configuration in `.prettierrc.json`

#### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
