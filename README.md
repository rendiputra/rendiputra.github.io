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

### Optimizing build for production
```bash
npx tailwindcss -o build.css --minify
```
