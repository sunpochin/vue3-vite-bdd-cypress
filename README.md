# vue3-vite-bdd-cypress

## Ref:
After reading these following posts I made bdd working in a vue3 vite project.

https://medium.com/@JoeTann/front-end-tutorial-on-behavior-driven-development-with-cucumber-cypress-and-jest-a7e28c517e1

https://stackoverflow.com/questions/72617008/cypress-cucumber-preprocessor-does-not-parse-feature-files

https://github.com/JoanEsquivel/cypress-cucumber-boilerplate

https://www.youtube.com/watch?v=bS9Q0_uKAs8&t=1181s
https://github.com/kylecoberly/knowledge/wiki/Cypress-Cucumber


```
npm run test:e2e
```
to see bdd results.

If any cypress error occurs, try:
```rm node_modules``` and ```npm i```

## Project Setup

```sh
npm install
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run build
npm run test:e2e # or `npm run test:e2e:ci` for headless testing
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

