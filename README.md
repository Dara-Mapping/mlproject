## End to End machine Learning Project

<!--
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

writing code in file setup.py 
before import package library 

from setuptools import find_packages, setup
from typing import List

and then call function setup ()
and then create function get_requirments() 


# create folder name {components} in src and create some files :
 __init__.py, 
data_ingestion.py
data_transformatin.py
model_trainer.py
-------------------------------------
# create folder name {pipeline} in src and then create some files:
__init__.py
predict_pipeline.py
train_pipeline.py
--------------------------------------
# create file some file under src folder:
logger.py
exception.py
utils.py
-----------------------------------
# write code in exception.py file

This code is meant to capture detailed information about an exception (file name, line number, and error message) and wrap it into a custom exception class so errors are clearer, more traceable, and easier to debug—especially in larger projects.

High-Level Purpose (TL;DR)
This code is designed to:

- Catch a Python error
- Extract where it happened (file name & line number)
- Format a human-readable error message
- Raise a custom exception with richer context than a normal error
👉 Very useful in production systems, data pipelines, ML projects, APIs, etc.

-----------------------------------

# write code in logger.py file

this is a logging setup script. Its purpose is to create a structured log file and record runtime information (events, status, errors) while your Python program runs.

Overall Purpose (TL;DR)
This code:

- Creates a timestamped log file
- Stores logs in a logs/ directory
- Configures Python’s logging module
- Records messages like “Logging has started” into that file
➡️ Useful for debugging, monitoring, and auditing your application.

---------------------------
# commit code and push to git repo 
git add .
git commit -m "logging and exception"



-->