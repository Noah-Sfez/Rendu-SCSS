# My SCSS Project

This is a project that follows the 7-1 architecture pattern for organizing SCSS files. The project includes a reset.scss file to ensure consistent styling across different browsers.

## Project Structure

The project is structured as follows:

- `scss/abstracts/_variables.scss`: Contains all the SCSS variables used throughout the project.
- `scss/abstracts/_functions.scss`: Contains all the SCSS functions used throughout the project.
- `scss/base/_reset.scss`: Resets all the default styles that the browser applies.
- `scss/base/_typography.scss`: Contains all the base styles related to typography.
- `scss/components/_buttons.scss`: Contains all the styles related to buttons.
- `scss/layout/_header.scss`: Contains all the styles related to the header of the website.
- `scss/layout/_footer.scss`: Contains all the styles related to the footer of the website.
- `scss/pages/_home.scss`: Contains all the styles specific to the home page.
- `scss/themes/_theme.scss`: Contains all the styles related to the theme of the website.
- `scss/vendors/_bootstrap.scss`: Contains all the Bootstrap styles used in the project.
- `css/main.css`: The main CSS file generated by compiling the SCSS files.

## Setup

To set up the project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the necessary dependencies.
4. Run the build command to compile the SCSS files into CSS.

## Usage

To use the project, include the `css/main.css` file in your HTML files. You can then add or modify the SCSS files as needed, and recompile the CSS file.

Remember to always modify the SCSS files, not the CSS file directly, as the CSS file will be overwritten when the SCSS files are compiled.