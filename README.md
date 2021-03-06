# QA Engineer Challenge

## Getting Started

- โ๏ธ &nbsp; Install the node version listed in `.nvmrc` (we recommend using [nvm](https://github.com/nvm-sh/nvm)).
- ๐ธ &nbsp; Install yarn (with `npm i -g yarn`)
- ๐งถ &nbsp; Install the project's dependencies (with just `yarn`)
- ๐ฒ &nbsp; Run Cypress (with `yarn test:cy`)
- ๐ &nbsp; Write tests

## Helpful Advice

- We almost exclusively use [`cypress-testing-library`](https://testing-library.com/docs/cypress-testing-library/intro/)
  to write our assertions. You're welcome to use them or not.

- At Air, we try to avoid to duplicate coverage; however, we can't provide you the function we use to forcibly
  authenticate and avoid the login or registration process for inner-app tests. Unfortunately, that means you'll
  want to login or register before you can make in-app assertions.

- We use real data in our integration tests, but you're welcome to use fixtures if that's what you're used to!
