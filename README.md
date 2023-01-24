An incredibly simple React app that exists for the sole purpose of showing us how to set up Cypress.

This is the companion respository for [Steve's Cypress course for Frontend Masters][course].

You can find [the main repository here][course].

[course]: https://github.com/stevekinney/cypress-examples

## Cypress on WSL2

- [Setup Cypress on WSL2](https://gist.github.com/pjobson/6b9fb926c59f58aa73d4efa10fe13654)

## Commands

- `cypress open` (user runs this, creates screen shots for debugging)

- `cypress run` (CI pipeline uses this)

- `npx` (Takes any binaries in the node modules and adds them to the path)

```bash
npx cypress open # starts the cypress electron app for testing 
```

## Getting started

1. run `npm install` to install dependencies