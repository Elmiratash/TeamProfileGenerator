# Team Profile Generator

![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)

## Description

This application was created to generate a team profile based on user input using the Inquirer module from Node.js and displaying the information on a newly created html page with a style sheet. This project demonstrates use of OOP and TDD using Jest.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)


## User Story

As a manager
I want to generate a webpage that displays my team's basic info
so that I have quick access to emails and GitHub profiles


## Technology

1. Node.js :

Node.js is an open-source and cross-platform JavaScript runtime environment. A Node.js app is run in a single process, without creating a new thread for every request. Node.js provides a set of asynchronous I/O primitives in its standard library that prevent JavaScript code from blocking.

2. Inquirer NPM package :

Inquirer.js strives to be an easily embeddable and beautiful command line interface for Node.js.

3. Jest NPM Package :

Delightful JavaScript Testing
Complete and ready to set-up JavaScript testing solution.
Failed tests run first. Fast interactive mode can switch between running all tests or only test files related to changed files.


## Installation

Clone this repository to use this application.
Navigate to the 'Develop' folder. To install necessary dependencies, run the following command :

npm i

Run this command to check all tests pass:

npm run test

The application will be invoked with the following command:

node app.js


## Usage

Run commands listed in Installation.
Running node app.js command will prompt user or manager series of questions to build team.
Once user finished building team, a HTML page 'team.html' will be generated in the 'output' folder.

Open this HTML file in the browser to see your team page.
View walk through video here - ![TeamProfile](https://user-images.githubusercontent.com/93406585/146301914-3733fe79-a56c-466d-b817-02c2408145d7.gif)


## Features

1. Used Node.js to build application which generates 'team.html' file dynamically by user's input.
2. Npm package 'Inquirer' is used.
3. 'Jest NPM Package' is used to follow test driven development and ensured that all tests pass.
4. Validated user input for email, ID's and office number.


## License

This project is license under MIT


## Contributing

Contributors should read the installation section.


## Tests

npm test


## Questions

If you have any questions about this projects, please contact me directly at elmira.tashvighi@gmail.com.
You can view more of my projects at https://github.com/elmiratash.
