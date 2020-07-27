# simple-page-template

Starting template for simple webpages.
It has build in linters, husky pre commit hook and script for building and live reloads.

## Files and folders structure

```bash
├── ./assets
│   ├── ./assets/css #External styles
│   ├── ./assets/fonts #Font files folder
│   ├── ./assets/img #Dir for images
│   ├── ./assets/scripts #JS files
│   │   └── ./assets/scripts/main.js
│   └── ./assets/scss #Internal styles
│       └── ./assets/scss/style.scss #Default style for page
├── ./index.html #Starting point for page
```

## Basic commands

### Run live server with reloads

```bash
npm run start-dev
```

### Build development version - without minification

```bash
npm run build-dev
```

### Build production version - minified

```bash
npm run build-prod
```

### Running linters

#### Check code formatting

```bash
npm run prettier-check
```

#### Checking JS code

```bash
npm run eslint
```

#### Checking CSS code

```bash
npm run stylelint
```

#### Checking page accessibility

```bash
npm run a11y
```

### Formatting code with Prettier

```bash
npm run prettier
```
