# Linting

Project has configured linting for styles and for jsx/js files

## JS | JSX

Linting for js and jsx is configured in .eslintrc.js.
Definitions for rules can be found at:
https://eslint.org/docs/rules/
https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/button-has-type.md

### Commands
Commands defined in package.json
  ```
  npm run lint
  ```

To fix auto-fixable current lint errors:
  ```
  npm run lint-fix
  ```
To lint project and debug linting process
  ```
  npm run lint-debug
  ```

## CSS | SCSS
Linting for styling is configured in .stylelintrc.js.
Definitions for rules can be found at:
https://github.com/stylelint/stylelint/blob/master/docs/user-guide/rules/list.md
https://github.com/kristerkari/stylelint-scss

### Commands
Commands defined in package.json
  ```
  npm run style-lint
  ```

To fix auto-fixable current lint errors:
  ```
  npm run style-lint-fix
  ```
