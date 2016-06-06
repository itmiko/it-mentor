# it-mentor
It-mentors - service what is help to connect mentor and mentee for study IT-technology.

## Technologies
- node@5.\*.\*
- npm@3.\*.\*
- mongodb@2.\*.\*

## Prerequirements
Make sure that your OS is up to date and MongoDB is installed.  
If no - make next steps:

For debian-like OS:  
Update your OS...
```
$ sudo apt-get update
$ sudo apt-get upgrade
```
... and set up Mongo:
```
$ sudo apt-get install mongodb
```
Check install:
```
$ sudo netstat -tnlp | grep mongo
```
Output must looks like that:
```
tcp        0      0 127.0.0.1:27017         0.0.0.0:*               LISTEN      4306/mongod
```

For Windows [click the link](https://docs.mongodb.com/v3.0/tutorial/install-mongodb-on-windows/)


## How to Install

### Install Node and NPM
Install [NVM](https://github.com/creationix/nvm) first  
For Windows [click the link](https://github.com/coreybutler/nvm-windows)  
For debian-like OS:

Go to [NVM GitHub repo](https://github.com/creationix/nvm) and follow the instruction or just put this command in your terminal  
```
$ wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.1/install.sh | bash
```
Close and reopen your terminal to start using nvm

After that install [node.js](https://nodejs.org/en/) and [npm](https://www.npmjs.com/)  
Run in terminal
```
$ nvm install 5
```
Check install:
```
$ node -v
$ npm -v
```

Then you should install bower and gulp
```
$ npm i -g bower
$ npm i -g gulp-cli
```
### Install Git
Install [git](https://git-scm.com)  
For Windows [click the link](https://git-scm.com/download/win)  
For debian-like OS:
```
$ sudo apt-get install git
```

### Clone project
Write next commands in terminal:
```
$ mkdir path/to/projects/folder
$ cd path/to/projects/folder
$ git clone https://github.com/itmozok-kiev/it-mentor.git
$ cd it-mentor
```

Install dependencies:
```
$ npm i
$ bower i
```

... and try to start
```
$ gulp serve
```

## Style & Rules
We are got accepted Airbnb Style Guide
[Read this](https://github.com/airbnb/javascript) and write your code using this style guide

- Tabs or Spaces? Set up your tab to 4 spaces!
- Use ES6
- Semicolon end lines
