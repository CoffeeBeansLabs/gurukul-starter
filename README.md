# Gurukul Starter
This is a starter boilerplate for candidates attending the Gurukul sessions.

## Get started

### Clone this repo in your machine

```
git clone git@github.com:CoffeeBeansLabs/gurukul-starter.git gurukul-jan22

# remove the origin of this repo in your project
git remote rm origin

# verify there are no remote links in your projects
git remote -v
```

Now you can create a repository in you github/gitlab account and push the changes there.

### Requirements for running the project locally
This is a Nodejs based project. You will need to have node installed in your machine.

### install dependencies with npm

```
npm install
```

## Conventions for writing test files

There are multiple ways of writing test files and all depends on how you'd like to see the tests for your code.

- Writing test files in the `__tests__` folder where you keep all your test files.
  - e.g. `src/logic.js`, & `__tests__/logic.test.js`


## Running the test cases

```
npm run test
```
