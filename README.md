# Disney+ Clone

A clone of Disney+ built with HTML, CSS, JavaScript, and Gulp for task automation. This project aims to replicate the interface and some basic functionality of the Disney+ streaming platform.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Build Tools](#build-tools)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Demo

You can see a live demo of the project [here]([https://github.com/analiceleite/clone_disney_plus/]).

## Features

- Fully responsive layout for different screen sizes.
- Replicates the main layout of Disney+ including the navbar, carousel, and media sections.
- Basic user interactions using JavaScript.
- Image optimization, CSS minification, and SASS compilation via Gulp.
- Automated build process with `gulp-sass`, `gulp-uglify`, and `gulp-imagemin`.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    
    bash
    
    Copiar código
    
    `git clone https://github.com/analiceleite/clone_disney_plus.git cd clone_disney_plus`
    
2. **Install dependencies:** Ensure you have [Node.js](https://nodejs.org/) installed, then run:
    
    bash
    
    Copiar código
    
    `npm install`
    
3. **Run the development server:**
    
    bash
    
    Copiar código
    
    `npm run dev`
    
    This will start Gulp and begin watching for file changes.
    
4. **Build the project:** To build the project for production (minifying and optimizing files), run:
    
    bash
    
    Copiar código
    
    `npm run build`
    

## Usage

After running `npm run dev`, you can edit the HTML, SCSS, or JavaScript files, and Gulp will automatically recompile and refresh the output. This makes it easy to see changes immediately.

If you want to just build the project without running the development server, use:

bash

Copiar código

`npm run build`

## Build Tools

This project uses Gulp for automation. The following Gulp tasks are available:

- `gulp sass`: Compiles SCSS files to CSS.
- `gulp uglify`: Minifies JavaScript files.
- `gulp imagemin`: Optimizes images.
- `gulp watch`: Watches for changes in files and runs respective tasks.

## Technologies

- **HTML5:** Structure of the web page.
- **CSS3 / SCSS:** Stylesheets and pre-processing with SASS.
- **JavaScript (ES6+):** User interactions and dynamic content.
- **Gulp:** Task automation (CSS and JS minification, image optimization, and SCSS compilation).
- **Node.js & npm:** Package management and build tools.

## Contributing

Feel free to submit issues or pull requests to contribute to this project. If you'd like to make major changes, please open an issue first to discuss what you would like to modify.

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.

## License

This project is licensed under the ISC License. See the LICENSE file for details.
