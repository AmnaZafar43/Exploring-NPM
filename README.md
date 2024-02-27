# Exploration of NPM

### Developer Name

Amna Zafar(2021-CS-27)

### ***Project Name:***

Exploration of NPM 

### *How to create and publish package*

1. Open cmd in folder in which you want to create project.Run `npm init -y` and package.json file is ready. 
2. Create index.js file and make any function which print name, perform calculation etc. In terminal run `npm link` .
3. Create test folder and script.js file in this folder. Now acquire the package by `const variable = require('string')`.
4. Now change directory and in test-folder again run `npm link`.
5. Now run `npm login` and login to your npm account.
6. Now run `npm publish`. Your package is successfully published. Additional node-modules folder is created which your folder.