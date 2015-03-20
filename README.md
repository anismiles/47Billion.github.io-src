# 47Billion.github.io-src

## For developers to setup the project for the first time

STEP 1- Install node modules using(This will fetch all the plugins needed to setup the environment e.g. all the grunt plugins) : npm install
STEP 2- Install bower dependencies using(This will fetch all the project specific dependencies declared as bower dependencies into the bower.json file) : bower install 
STEP 3- Build the project using grunt command : grunt --force
STEP 4- To run the app while development do: grunt serve
This will run the server on 9000 port and will automatically open the home page on your default browser.
To run the project with concatenated and minified files repeat: STEP-3 and then : grunt serve:dist
