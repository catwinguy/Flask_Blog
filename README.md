# FlaskProject
Purpose: Creating a blog using Flask Module (Python)

Status: In-Progress



## Installing Dependencies
Install the pipenv module
```
pip install pipenv
```

Install the depencies as a user
```
pipenv install --ignore-pipfile
```

Install the depencies as a developer
```
pipenv install --dev
```

## Running This App
Start the Flask App with the command: ```pipenv run python main.py```.

## Extra Pipenv Commands
View top level dependencies and their sub-dependencies
```
pipenv graph
```

Check for security and up-to-date dependencies
```
pipenv check
```

Run the environment shell
```
pipenv shell
```

Pipenv Help: https://realpython.com/pipenv-guide/