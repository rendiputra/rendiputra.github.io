# Documentation

## Installation
### Install dependency
```bash
$ npm install
```
 
### Start the Tailwind CLI build process
Run the CLI tool to scan your template files for classes and build your CSS.
```bash
$ npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

Change 
```html 
<link href="src/build.css" rel="stylesheet">
```
To
```html
<link href="src/output.css" rel="stylesheet">
```

### Optimizing build for production
```bash
npx tailwindcss -o build.css --minify
```
