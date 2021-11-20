# python-newsfeed
![{data.license}](https://shields.io/badge/license-MIT-green)

## Description
    
Python Newsfeed is a web server powered by Python connected with its own MySQL database using the SQLAlchemy ORM. Every logged in user has access to their own dashboard where they're able to create new posts. The posts may be commented and upvoted by other logged in users, but posts may only be edited or deleted by the original publisher.


## Content

* [GitHub Repository](https://github.com/Rudy-Menjivar/python-newsfeed/)

* [Heroku Deployment](https://just-technews.herokuapp.com/)

* [Installation](#installation)

* [Usage](#usage)

* [Contributing](#contributing)

* [Questions](#questions)

## Installation


## Create a Virtual Environment

Run the following command to install a self-contained directory that maintains its own version of Python and its own library dependencies. This allows multiple Python projects to reside on the same machine without interfering with each other.
```
python -m venv venv
```


## Start Virtual Environment

Python has its own package manager, called pip. The pip command installs along with Python, requiring no further setup. However, we need to ensure that the virtual environment is running so that dependencies get put into the right place.

If you're using Windows, run the following command with Windows PowerShell from the root directory of your project:
```
.\venv\Scripts\activate
```
If you're using macOS, run the following command:
```
. venv/bin/activate
```


## Install Flask

Once the virtual environment activates, run the following command to install Flask:
```
pip install flask
```


## Start the Flask server (from Windows PowerShell if using Windows)
```
python -m flask run
```
  

## Usage

Run this command to invoke this application:
```
python -m flask run
```
  

## Contributing
    
Any community contributions will help in achieving this project's success, so any help is greatly appreciated.
    
To participate in this project, please review the following guidelines:
    
1. Create a branch for your update (after forking and cloning)
    
   `git checkout -b <branchName>`
    
2. Make changes or additions to new or existing file & stage it
    
   `git add <fileName.ext>`
    
3. Commit your file by adding comments about code enhancements
    
   `git commmit -m <your code comments>`
    
4. Push your changes with your remote branch name
    
   `git push -u origin <branchName>`
    
5. Finally, submit [feature requests and bugs](https://github.com/Rudy-Menjivar/python-newsfeed/issues) and open a [pull request](https://github.com/Rudy-Menjivar/python-newsfeed/pulls)
  

## License

Copyright (c) Rudy-Menjivar. All rights reserved.
    
Licensed under the [MIT](./LICENSE.txt) license.
  

## Questions
  
If you have any questions, then feel free to contact me at rudy.menjivar@gmail.com. You may also access my complete work at [GitHub](https://github.com/Rudy-Menjivar).