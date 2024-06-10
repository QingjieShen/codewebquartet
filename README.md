## Introduction
This framework is designed to provide a set of well-designed, responsive, and customizable class names to streamline your web development process. Built on the power of SASS and organized through SASS partials, this framework allows you to quickly apply consistent styling across your projects while maintaining the flexibility to modify default settings to fit your unique design needs.

## Getting Started
To start using the custom CSS Framework, following these steps:

1. clone the repository:
```
https://github.com/QingjieShen/codewebquartet
```
2. Install dependencies:
```
npm install sass
```
3. Compile the SASS files:
```
npm run scss
```
4. Include the compiled CSS in your HTML file
```
<link rel="stylesheet" href="path/to/compiled/css/styles.css">
```
> If you are using the example file which is "index.html", then the link will be:
```
<link rel="stylesheet" href="css/style.css">
```

## Technology
This framework leverages the following technologies:
### SASS: 
A powerful CSS preprocessor that extends CSS with variables, nested rules, and more.
### SASS Partials: 
Modular SASS files that allow for better organization and maintainability of styles.

## Customization
This CSS framework provided a base style and a variety of utility classes to manage list styles, background colors, border styles, border radius, button styles, table styles, box shadows, flex and grid displays, and responsiveness. All variables are defined in the `_variables.scss` file, while the main file is `_codewebquarted.scss`, where all other module files are imported and compiled.
### Customization Tips

####  _base.scss
- **Purpose**: Contains the default styles for HTML elements and some background, color, and border styles.
- **How to Customize**: Open _base.scss and modify the styles for the HTML elements or change the background, color, and border styles as needed.

#### _effect.scss
- **Purpose**: Defines styles for box shadows.
- **How to Customize**: Open _effect.scss and modify the box-shadow properties to achieve the desired shadow effects for your elements.

#### _filter.scss
- **Purpose**: Contains styles for various CSS filters.
- **How to Customize**: Open _filter.scss and adjust the filter properties such as blur, brightness, contrast, etc., to suit your design requirements.

#### _fontfamily.scss
- **Purpose**: Imports and sets the font families used in the framework.
- **How to Customize**: Open _fontfamily.scss and update the font-family definitions to include the fonts you want to use in your project.

#### _layout.scss
- **Purpose**: Manages media queries and responsive layout styles.
- **How to Customize**: Open _layout.scss and modify the media queries to adjust the responsive behavior of your layout according to different screen sizes.

#### _typography.scss
- **Purpose**: Contains all the styles related to typography.
- **How to Customize**: Open _typography.scss and change the typography settings, including font sizes, text alignments, text decoration, etc..

#### _variables.scss
- **Purpose**: Defines all the variables used throughout the framework.
- **How to Customize**: Open _variables.scss and modify the values of the variables to change the default settings. This includes colors, spacings, font sizes, and more. Any change here will be reflected across the entire framework.

### Examples

#### Change the black background color
- Open _variables.scss.
- Locate the variable for the target background color (which is $bg-black).
- Change its value to your desired color:
```
$bg-black: #3498db; // New primary color
```

### Change the Default Font Family:
- Open _fontfamily.scss.
- Modify the @import statements and font-family definitions to include your desired fonts
```
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

body {
    font-family: 'Roboto', sans-serif;
}
```

### Recompile the SASS Files:
- After making your changes, recompile the SASS files to apply the customizations:
Run scss to compile the SASS files
```
npm run scss
```
