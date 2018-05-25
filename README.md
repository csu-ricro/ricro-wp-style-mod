# ricro-wp-style-mod

SCSS files for creation of style extensions and modifications for VPR WordPress template.

## Getting Started

    npm i

Install dependencies

## Development

### ricro-wp-style-mod

    npm start

Start the watch script for the SCSS file in the `src/index.scss` directory to develop on the entire project.

### bootstrap4

    npm start:bootstrap4

Start the watch script for the SCSS file in the `bootsrap4/src/index.scss` directory to develop only on the bootstrap4 section of the project.

## Build and Deploy

### ricro-wp-style-mod

    npm run build

Build the SCSS from `src/index.scss` and use the output in `dist/ricro-wp-style-mod.css` to
minify the file to `dist/ricro-wp-style-mod.min.css`.

### bootstrap4

    npm run build:bootstrap4

Build only the SCSS from `bootstrap4/src/index.scss` and use the output in `bootstrap4/dist/colostate-ricro-bootstrap4.css` to
minify the file to `bootstrap4/dist/colostate-ricro-bootstrap4.min.css`.
