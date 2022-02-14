# Creating a TypeScript React App

- [TypeScript > Create React App Docs](https://create-react-app.dev/docs/adding-typescript/)
- [Getting Started with TypeScript and React](https://create-react-app.dev/docs/adding-typescript/#getting-started-with-typescript-and-react)

# Linter setup with ESLint

Just use this starter: [Typescript React ESLint Cypress Starter with Create React App](https://github.com/benhunter/typescript-react-eslint-starter)

[ESLint Getting Started](https://eslint.org/docs/user-guide/getting-started)

```
yarn add --dev eslint
```

Create config with wizard:

```
yarn create @eslint/config
```

- [x] TODO [ESLint Compatibility Rules](https://github.com/typescript-eslint/typescript-eslint/blob/main/packages/eslint-plugin/src/configs/eslint-recommended.ts)
- [x] TODO AirBnB Lint rules for TypeScript

# Jest

- Jest is already included by Create React App.

# Cypress

[Cypress.io](https://www.cypress.io/)

```
yarn add cypress --dev 
```

See run scripts in package.json.

See .gitignore for ignoring Cypress test output.

## Cypress Testing Library

- [Cypress Testing Library](https://testing-library.com/docs/cypress-testing-library/intro/)

```
yarn add --dev @testing-library/cypress
```

## Cypress Examples

- [ ] Remove `/cypress/integrations/*`
