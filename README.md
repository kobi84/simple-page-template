# simple-page-template

Starting template for simple webpages.
It has build in linters, husky pre commit hook and script for building and live reloads.

## Files and folders structure

```bash
├── ./page
│   ├── ./page/assets
│   │   ├── ./page/assets/css #External styles
│   │   ├── ./page/assets/fonts #Font files folder
│   │   ├── ./page/assets/img #Dir for images
│   │   ├── ./page/assets/scripts #JS files
│   │   │   └── ./page/assets/scripts/main.js
│   │   └── ./page/assets/scss #Internal styles
│   │       └── ./page/assets/scss/style.scss
│   └── ./page/index.html #Starting point for page
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
