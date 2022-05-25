[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
#Conversion Tool Mini-Project (Flask)

This project has been created for you to practice unit testing using Pytest on a Flask project (pytest-flask). The source code contains a conversion tool that will convert numbers to different bases (binary, decimal and hexadecimal). You can use it to develop a set of scenarios needed to test all of the source code. Note that the suggested solutions are available in different branches of the directory structure.
## Prerequisites
- Install Python 3: Python 3 download
- Install Git: Git download
## Installation
1. Download the Project to Your Local Directory:
```shell
git clone https://github.com/OpenClassrooms-Student-Center/4425126-testing-python-flask.git 
cd 4425126-testing-python-flask
```

2. Set up a Virtual Environment:
- Create the virtual environment: `python -m venv venv`
- Activate the virtual environment:
  - Windows: `venv\Scripts\activate.bat`
  - Unix/MacOS: `source venv/bin/activate`
3. Install project dependencies
```
pip install -r requirements.txt
```
 
## Run
- Run the script using the following command: `flask run`

## Solutions
Suggested solution for unit testing using pytest-flask:
```
git checkout pytest-test
pytest -v tests/
```