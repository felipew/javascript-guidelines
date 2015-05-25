# Code Style - Javascript

## Airbnb guidelines

Here are the Airbnb code guidelines:

1. Code GuideLine: https://github.com/airbnb/javascript
1. Code Guideline ES5-Only: https://github.com/airbnb/javascript/tree/master/es5 


Here are the suggested modifications to the above coding guidelines:

1. Change bla bla bla to bla bla bla
1. Change etc etc etc to yoda yoda yoda
1. Happy Towell Day!

## Rules

The best approach to use these guidelines is to add a linter to your workflow, following are some rules to enforce the guidelines on the repo.

1. Do not talk about the fight club.
1. Always lint your code during development (plugins could be checked below)
1. Always lint your code before build/deploy
1. ONLY deploy with NO warnings (pre-commit/pre-push on main branches)



# Linting your code

## Tools

### JSCS

URL:  https://github.com/jscs-dev/node-jscs

JSCS is a code style linter for programmatically enforcing your style guide. You can configure JSCS for your project in detail using over 120 validation rules, including presets from popular style guides like jQuery, Airbnb, Google, and more. (more info on the repo).

Just put a .jscs.json containing the recommended rules and the linters will do their jobs.
Here are the recommended file: https://github.com/jscs-dev/node-jscs/blob/master/presets/airbnb.json 

### Grunt-jscs

URL: https://github.com/jscs-dev/grunt-jscs

Integrate jscs into your grunt task.

### Gulp-jscs

URL: https://github.com/jscs-dev/gulp-jscs 

Integrate jscs into your gulp task.

## Plugins

Using a linter can at the end of every development cycle can be overwhelming and generate re-work, to optimize the workflow there are plugins to major IDEs and text editors to ensure a "lint gutter" and help to employ a better and readable code.

### Sublime

URL: https://github.com/SublimeLinter/SublimeLinter-jscs

### Atom

URL: https://github.com/AtomLinter/linter-jscs 

### WebStorm

URL: https://github.com/idok/jscs-plugin 

### Brackets

URL: https://github.com/globexdesigns/brackets-jscs






