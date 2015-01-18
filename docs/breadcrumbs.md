# Setting up a development environment

## Git setup

* git config --global user.name "User Name"
* git config --global user.email "username@doit.com"
* git config --global core.autocrlf true  (for Windows)

## Express generator install

* npm install -g express-generator

## Install node modules

* npm install

## WebStorm run config for unit tests:

* Add a run configuration for Node.js with:
  * Node interpreter: set to pertinent node.exe
  * Working directory: set to here4ye project directory
  * Javascript file: set to jasmine-node-runner.js in here4ye project directory

# MongoDB operations

* From a DOS console as Admin:
  * mongod --config "C:\Program Files\MongoDB 2.6 Standard\mongod.cfg"

# Heroku operations

* heroku login
* heroku logout
