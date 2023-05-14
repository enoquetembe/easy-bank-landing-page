# Project Structure

The following document is an overview of the main directories and files in the project:

- `public/`: contains the public assets for the application
- `src/`: contains the all files for the application
- `src/styles`: contains all CSS application files to sytle the application
- `src/script`: contains all JavaScript application files
- `src/assets`: contains the  assets (e.g. images, fonts) used in the application.
- `README.md`: contains the project overview and setup instructions.

## Public

The `public/` directory contains public asses used in the application (favicon.ico):

## Src

The `src/` directory contains the folders and files that make up the application and index.html must be there. For example:

- `src/index.html`
- `src/assets/**`
- `src/styles/**/*.css`
- `src/script/**/*.js`  

## Assets

The `src/assets/` directory contains any assets (e.g. images, fonts) used in the application. These assets can be accessed directly by the browser. For example:

- `src/assets/logo.png`: the logo image used in the application
- `src/assets/fonts/OpenSans-Regular.ttf`: the Open Sans font used in the application.


## Styles
The `src/styles` contains all CSS application files to sytle the application. We are not using any frameworks or libraries to style our application. Each part must be in a diffent CSS file and must be imported in the CSS index file. For example:

- The `src/styles/global.css`: The file contains the global CSS styles and utilities used in the application. We are not using any framework to style the application.

- The `src/styles/index.css`: The main CSS file.

- The `src/styles/header`: The file contains CSS to style the header of the application.

- The `src/styles/header`: The file contains CSS to style the footer of the application.

And so on.

## Scripts
The `src/scripts` contains all JavaScript application files to add any iteration to the application. We are using ES6 modules, each part must be in a different JavaScript file and must be imported in the javascript index file. For example:

- The `src/scripts/index.js`: The main JavaScript file.

- The `src/scripts/modules/`: This directory containis all JavaScript application modules.

- The `src/scripts/modules/mobile-menu.js`: The file contains JavaScript code to add a mobile navigation to the application.

- The `src/scripts/modules/accordion.js`: The file contains JavaScript code to add accordion animation to the application.

And so on.

