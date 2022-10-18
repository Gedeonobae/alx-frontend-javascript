# 0x00. ES6 Basics

## Concepts

<p><i>For this project, we expect you to look at these concepts: </i></p>

##  Software Linter
Definition

A software linter also known as a “linter” is a tool used to identify and report potential issues (syntax errors, undeclared variables, etc.) in a program. It can even report convention or style inconsistencies. It does so by highlighting them so that the programmer is aware, so changes can be made. There are a wide variety of linters as well as lint rules for specific programming languages and even for software frameworks.

There are typically two ways to lint code:

    Actively
    Passively

Active

Active checking is typically achieved by running a monitor tool that is constantly checking the file that your working on in order to spot inconsistencies and possible errors (e.g., having a specific linter along with some lint rules installed as a plug-in in your Code Editor).
Passive

Passive checking is done by taking a piece of code, and manually running it through a tool to identify potential issues. For example, copying and pasting your code into a specific linter tool, or running the linter against a specific file using the command line. This tool can be installed locally or be available as a service (e.g., website on the Internet).
Examples

Screenshot of an active linter pycodestyle (Python) integrated into Visual Studio Code


## Resources
## Read or Watch
* <a href = "https://www.w3schools.com/js/js_es6.asp">  ECMAScript 6 - ECMAScript 2015</a>
* <a href = "https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements"> Statements and declarations </a>
* <a href = "https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions"> Arrow functions </a>
* <a href = "https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters"> Default parameters </a>
* <a href = "https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters"> Rest parameter </a>
* <a href = "https://towardsdatascience.com/javascript-es6-iterables-and-iterators-de18b54f4d4"> Javascript ES6 — Iterables and Iterators </a>

## Requirements
* All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
* Allowed editors: vi, vim, emacs, Visual Studio Code
* All your files should end with a new line
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the js extension
* Your code will be tested using the <a href = "https://jestjs.io/">Jest Testing Framework </a>
* Your code will be analyzed using the linter <a href = "https://eslint.org/"> ESLint</a> along with specific rules that we’ll provide
* All of your functions must be exported



## Setup 
### Install NodeJS 12.11.x
<p> (in your home directory):  </p>

```
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y

```
<br>

```
$ nodejs -v
v12.11.1
$ npm -v
6.11.3

```
<br>

## Install Jest, Babel, and ESLint
<p> in your project directory: </p>

* Install Jest using: npm install --save-dev jest

* nstall Babel using: npm install --save-dev babel-jest @babel/core @babel/preset-env

* Install ESLint using: npm install --save-dev eslint


## Configuration files

### package.json
### package.json 


### babel.config.js

### .eslintrc.js

Finally…

Don’t forget to run npm install from the terminal of your project folder to install all necessary project dependencies.
