## End to End machine Learning Project

``create enviroment``
~ conda create -p venv phthon = 3.13-y

`` activate enviroment ``
~ conda activate venv/

~ git add README.md 
~ git commit -m "Frist commit"
~ git status # check git status
~ git branch -M main 
~ git remote add origin https://github.com/Dara-Mapping/mlproject.git
~ gti  remove -v
~ git config --global user.email
~ git config --global user.name
~ git push -u original main

`` go to git Repo to creat file .gitignore accept python ``
~ git pull

### Setup.py to setup project structure
``The setup.py file is a Python script that provides metadata and instructions for building, distributing, and installing a Python package. It uses the setuptools library to define package details such as its name, version, dependencies, and included modules. ``

``create requirements.txt file``

<!-- writing code in file setup.py 
before import package library 

from setuptools import find_packages, setup
from typing import List

and then call function setup ()
and then create function get_requirments() -->

