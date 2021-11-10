# progessive-budget

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

# Table of Contents:
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [Questions](#questions)

# Description
Add functionality to our existing Budget Tracker application to allow for offline access and functionality.
The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

<p>
    <img src="images/dashboard.PNG" width="700" height="300"/></br></br>
    <img src="images/exercise.PNG" width="500" height="500"/></br></br>
</p>

The HTTP methods that the application used are 
* GET 
* POST

The application also require npm modules 
* express
* mongoose
* morgan
* compression
* lite-server

## Installation
**On console, run to install**
```command line
npm install 
npm i express
npm i mongoose
npm i morgan
npm i compression
npm i lite-server
```
To install heroku, download it from heroku website<br> 
or
```command line
npm install -g heroku
```

**Deploy to heroku**

```
heroku create app'name
git init
git add .
git commit -m "initial commit"
git push heroku master
heroku open
```
**Add a remote to your local repository** 

* heroku git:remote app's name

**Command to confirm that a remote named heroku has been set for**
* git remote -v

## Usage
To run on local host 
```command line
node server.js
```

**Run on Heroku** <br>
* Application deployed at live URL: 

## Contributing
**Create**<br> 
repository on GitHub<br>
**Clone** <br>
project to local machine, <br>
**Add** <br>
what you have done,<br>
**Commit** <br>
what you have changed, <br>
**Push** <br>
what you have done to GitHub<br>

## Questions
If you have any question about the application, feel free to contact me on GitHub.

* Github: https://github.com/jamesgli520/progessive-budget

* Email: mailto.jamesgli@gmail.com
