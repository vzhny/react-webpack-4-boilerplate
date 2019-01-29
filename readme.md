# React Boilerplate Using Webpack 4

My personal webpack 4 config setup for developing in React. Followed the steps posted [here](https://auralinna.blog/) as well as the Webpack docs.

## Features

- Jest and react-testing-library for React and general testing functionality (setup was done following [this](https://link.medium.com/fhDZqcKLNT) article).
- Eslint, using the airbnb-base config, for code linting.
- Code splitting for faster web app loading.
- Aliasing for ease of use when importing modules and components -- use `@` in imports to point to `/src/`.
- Favicon support included -- simply replace favicon.ico in the public folder.
- (S)CSS Modules and SVG imports fully supported.
- Ability to use CSS libraries without it conflicting with class name hashing.
- Reach router included for single page application functionality.

## To-do List

- Add service worker logic and mainfest file.
