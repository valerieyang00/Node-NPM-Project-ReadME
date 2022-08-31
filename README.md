# Node-NPM-Project-ReadME
## Steps for new Node/NPM Project
* Create a new folder for the project 
* `npm init` in the project folder to initialize NPM (`npm init -y` to skip all the steps and accept default values)
** `index.js` is the default that node will look for unless a different file name was specified in set up**
* `node filename` to run the program in Node
### Node Module Notes:
* `module.exports` to export modules. ex: `module.exports.functionName =`
* To import: `const varName = require("file path")` then use dot notation to run functions stored in the export js file
** Make sure the code is encapsulated in the `module.exports` for it to import/run**
### Node Packages Notes:
* In command line, `npm i {npm name}` to install in the directory you want. Use `npm i -g {npm name}` to globally install
* Create `index.js` in the folder to write codes 
* Run NPM in the terminal
* Before you add/commit to remote Github, make sure to create `.gitignore` file to include `node_modules` and any other files that should not be stored remotely

## Steps for cloning and setting up a repo with node packages
* Fork and Clone repo to your local repository
* Open the files and look at the `dependencies` listed inside the `package.json` file which is the npm that needs to be installed to get the `node_modules` that was excluded from the clone
* Run `npm install` or `npm i` in the terminal to initiate download. `node_modules` should appear in the folder.
* Make sure `node_module` is in the `gitignore` file before committing to remote repository




