# eslint-config
eslint configurationg for my projects

# React + Typescript + Vite

[YAML Rule File](./react-typescript-vite/.eslintrc.yml)

This ruleset is used in React + Typescript + Vite projects. Some of the considered circumstances are:

* programmers have different levels of skills
* code integration and delivery is expected at the end of the project
* portions of code are written without strict supervision

To solve the above mentioned problems, the ruleset is defined such that:

* [airbnb style](https://github.com/airbnb/javascript) is selected as base
* slight modification is done such that
  - tutorial-guided codes pass
  - minimum readability rules are enforced
  - some simple rules to help javascript coders adapt to typescript
  - design patterns are consistent with those of react and vite
