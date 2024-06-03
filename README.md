## Introduction
This framework is designed to provide a set of well-designed, responsive, and customizable class names to streamline your web development process. Built on the power of SASS and organized through SASS partials, this framework allows you to quickly apply consistent styling across your projects while maintaining the flexibility to modify default settings to fit your unique design needs.

## Getting Started
To start using the custom CSS Framework, following these steps:

1. clone the repository:
```
https://github.com/QingjieShen/codewebquartet
```
2. Navigate to the project directory:
```
cd codewebquartet
```
3. Install dependencies:
```
npm install sass
```
4. Compile the SASS files:
```
sass --watch main.scss css/style.css
```
5. Include the compiled CSS in the HTML file
```
<link rel="stylesheet" href="path/to/compiled/css/styles.css">
```
> If you are using the example file which is "index.html", then the link will be:
```
<link rel="stylesheet" href="css/style.css">
```

## Technology
This framework leverages the following technologies:

#### SASS: 
- A powerful CSS preprocessor that extends CSS with variables, nested rules, and more.
#### SASS Partials: 
- Modular SASS files that allow for better organization and maintainability of styles.

## Built-in Classes
#### Layout
- container:
- row: 
- col: 
#### Flexbox & Grid
- d-flex:
- flex-row:
- flex-column: 
- grid: 
- grid-cols-2: 
#### Spacing
- All direction margin:
    - m-0
    - m-1
    - m-2
    - m-3
    - m-4
    - m-5
- x-axis margin:
    - mx-0
    - mx-1
    - mx-2
    - mx-3
    - mx-4
    - mx-5
- y-axis margin:
    - my-0
    - my-1
    - my-2
    - my-3
    - my-4
    - my-5
- top margin:
    - mt-0
    - mt-1
    - mt-2
    - mt-3
    - mt-4
    - mt-5
- right margin:
    - mr-0
    - mr-1
    - mr-2
    - mr-3
    - mr-4
    - mr-5
- bottom margin:
    - mb-0
    - mb-1
    - mb-2
    - mb-3
    - mb-4
    - mb-5
- left margin:
    - ml-0
    - ml-1
    - ml-2
    - ml-3
    - ml-4
    - ml-5
- All direction padding:
    - p-0
    - p-1
    - p-2
    - p-3
    - p-4
    - p-5
- x-axis padding:
    - px-0
    - px-1
    - px-2
    - px-3
    - px-4
    - px-5
- y-axis padding:
    - py-0
    - py-1
    - py-2
    - py-3
    - py-4
    - py-5
- top padding:
    - pt-0
    - pt-1
    - pt-2
    - pt-3
    - pt-4
    - pt-5
- right padding:
    - pr-0
    - pr-1
    - pr-2
    - pr-3
    - pr-4
    - pr-5
- bottom padding:
    - pb-0
    - pb-1
    - pb-2
    - pb-3
    - pb-4
    - pb-5
- left padding:
    - pl-0
    - pl-1
    - pl-2
    - pl-3
    - pl-4
    - pl-5
#### Sizing
- Absoulte width
    - w-100
    - w-200
    - w-300
    - w-400
    - w-500
    - w-600
    - w-700
    - w-800
    - w-900
- Absoulte height
    - h-100
    - h-200
    - h-300
    - h-400
    - h-500
    - h-600
    - h-700
    - h-800
    - h-900
- Percentage width
    - wp-1
    - wp-2
    - wp-3
    - wp-4
    - wp-5
    - wp-6
    - wp-7
    - wp-8
    - wp-9
    - wp-10
    - w-screen
- Percentage height
    - hp-1
    - hp-2
    - hp-3
    - hp-4
    - hp-5
    - hp-6
    - hp-7
    - hp-8
    - hp-9
    - hp-10
    - h-screen
#### Typography
- Font Family
    - font-sans
    - font-serif
- Font Size
    - text-1
    - text-2
    - text-3
    - text-4
    - text-5
    - text-6
- Font Style
    - text-regular
    - text-ligth
    - text-medium
    - text-bold
    - text-light
    - text-regular-italic
    - text-ligth-italic
    - text-medium-italic
    - text-bold-italic
    - text-light-italic
- Letter Spacing
    - tracking-1
    - tracking-2
    - tracking-3
    - tracking-4
    - tracking-5
- Line Height
    - leading-1
    - leading-2
    - leading-3
    - leading-4
    - leading-5
- Text Align
    - text-left
    - text-center
    - text-right
    - text-justify
    - text-start
    - text-end
- Text Color
    - text-black
    - text-dark
    - text-orange
    - text-gray
    - text-bone
- Text Decoration
    - text-underline
    - text-overline
    - text-middleline
    - text-noline
#### Backgrounds
- Background Colors
    - bg-black
    - bg-dark
    - bg-orange
    - bg-gray
    - bg-bone
#### Borders
- Border Radius:
    - rounded-0
    - rounded-1
    - rounded-2
    - rounded-3
    - rounded-4
    - rounded-5
    - rounded-tl-0
    - rounded-tl-1
    - rounded-tl-2
    - rounded-tl-3
    - rounded-tl-4
    - rounded-tl-5
    - rounded-tr-0
    - rounded-tr-1
    - rounded-tr-2
    - rounded-tr-3
    - rounded-tr-4
    - rounded-tr-5
    - rounded-br-0
    - rounded-br-1
    - rounded-br-2
    - rounded-br-3
    - rounded-br-4
    - rounded-br-5
    - rounded-bl-0
    - rounded-bl-1
    - rounded-bl-2
    - rounded-bl-3
    - rounded-bl-4
    - rounded-bl-5
- Border Width:
    - border-0
    - border-1
    - border-2
    - border-3
    - border-4
    - border-5
- Border Color:
    - border-black
    - border-dark
    - border-orange
    - border-gray
    - border-bone
- Border Style:
    - border-solid
    - border-dashed
    - border-dotted
    - border-double
    - border-hidden
    - border-none
    - border-bottom-solid
    - border-bottom-dashed
    - border-bottom-dotted
    - border-bottom-double
    - border-bottom-hidden
    - border-bottom-none
    - border-top-solid
    - border-top-dashed
    - border-top-dotted
    - border-top-double
    - border-top-hidden
    - border-top-none
    - border-right-solid
    - border-right-dashed
    - border-right-dotted
    - border-right-double
    - border-right-hidden
    - border-right-none
    - border-left-solid
    - border-left-dashed
    - border-left-dotted
    - border-left-double
    - border-left-hidden
    - border-left-none
#### Effects
- Box Shadow Size:
    - box-shadow-0
    - box-shadow-1
    - box-shadow-2
    - box-shadow-3
    - box-shadow-4
    - box-shadow-5
- Box Shadow Opacity:
    - box-opacity-0
    - box-opacity-1
    - box-opacity-2
    - box-opacity-3
    - box-opacity-4
    - box-opacity-5

#### Filters
- Blur:
    - blur-0
    - blur-1
    - blur-2
    - blur-3
    - blur-4
    - blur-5
- Brightness:
    - bright-0
    - bright-1
    - bright-2
    - bright-3
    - bright-4
    - bright-5
- Contrast:
    - contrast-0
    - contrast-1
    - contrast-2
    - contrast-3
    - contrast-4
    - contrast-5

#### Tables
- Table Border
    - border-collapse
    - border-separate
- Table Border Spacing
    - table-boarder-spacing-0
    - table-boarder-spacing-1
    - table-boarder-spacing-2
    - table-boarder-spacing-3
    - table-boarder-spacing-4
    - table-boarder-spacing-5
    - table-boarder-x-spacing-0
    - table-boarder-x-spacing-1
    - table-boarder-x-spacing-2
    - table-boarder-x-spacing-3
    - table-boarder-x-spacing-4
    - table-boarder-x-spacing-5
    - table-boarder-y-spacing-0
    - table-boarder-y-spacing-1
    - table-boarder-y-spacing-2
    - table-boarder-y-spacing-3
    - table-boarder-y-spacing-4
    - table-boarder-y-spacing-5
- Table Layout
    - table-auto
    - table-fixed
#### Forms
- Inputs:
    - form-input
    - form-textarea
    - form-select
    - form-checkbox
    - form-radio
    - form-multiselect
- Buttons:
    - btn
    - btn-primary
    - btn-secdonary
- form-control: Styles input elements.
- form-group: Wraps form elements together.
- btn, .btn-primary, .btn-secondary: Styles buttons with different themes.
#### Lists
- List Style Type:
    - list-none
    - list-disc
    - list-decimal
#### Links
- Link Style:
    - link-normal
    - link-activated