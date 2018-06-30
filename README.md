<p align="center">
    <h2 align="center">Origami</h2>
</p>
<p align="center">
    A mobile-first front-end framework for written for minimal, elegant web design.
</p>
<br/>
<br/>

## 1. Getting Started

#### Installation
It's rather easy. Start by cloning or [downloading](https://github.com/benjamin-farnham/origami/archive/master.zip) directly and include the origami.min.css file along with the origami.min.js file (with the script preferably before the closing body tag) in your HTML.

```html
<!DOCTYPE html>
<html lang="en" class="no-js"><!-- no-js class allows a small javascript check -->
    <head>
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta charset="UTF-8">

        <!-- Origami <link> tag -->
        <link href="path/to/origami.min.css" rel="stylesheet" type="text/css">
    </head>
    <body>
        <!-- Your content here -->

        <!-- Origami <script> tag -->
        <script type="text/javascript" src="path/to/origami.min.js"></script>
    </body>
</html>
```

No CDN yet. But it is in the plans.

## 2. Features

- 12 column grid
    - Push, pull, & offset
- Flexbox
    - Rows & columns
    - Justify, alignment, & align-self
    - Ordering
    - etc.
- Basic element styles
    - Buttons
    - Cards
    - Form elements
        - Text inputs
        - Textareas
        - Select dropdowns
        - Checkboxes and radios
        - Range selector
        - Datepicker
        - File upload
- Helpers
    - Spacing (margins, padding)
    - Height (set vh heights)
    - Text alignment
    - Text size
    - Material shadows
    - Hide classes
    - Responsive iframes / ratio containers
- Quick toggle using HTML5 data attributes (build your own modals, navs, etc.)
- ie11 + support
- Fallbacks styles for browsers without JavaScript

Included are a lot of the tools to build and scale a website quickly. Until the doc site is up, a test page (demo.html) has been included. As for the Javascript, no dependencies are required. It was written with ES5 and is currently there to enhance user experience with forms and to add quick toggle abilities (to create your own custom modals and navigations).

## 3. In the works...

- Navigation
- Footer
- Drag'n'drop file uploads
- Button ripple effect on click
- Notifications / Toasts
- Modal
