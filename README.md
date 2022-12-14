# Electron Template

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

The goal of this project is to streamline the process of getting CI/CD set up for an electron app using Typescript,
React, Redux and Material UI

# Bugs

Still need to figure out the release part correctly. Currently, tags get bumped for every build, I think whether it
passes or not. Need to make sure only builds that pass bump the release number.

# Getting Started

Install dependencies with `yarn`

```
yarn
```

Start the server on `localhost:3001`

```
yarn start
```

# Contributing

The app should be configured to automatically update as you make changes and save them.

# Releases

In order to kick off a patch, minor or major release, use the following git commit messages:

* Breaking Changes should start with the word `BREAKING CHANGE:` with a space or two newlines. The rest of the commit
  message is then used for this.
* `feat:` A new feature
* `fix:` A bug fix
* `docs:` Documentation only changes
* `style:` Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* `refactor:` A code change that neither fixes a bug nor adds a feature
* `perf:` A code change that improves performance
* `test:` Adding missing or correcting existing tests
* `chore:` Changes to the build process or auxiliary tools and libraries such as documentation generation