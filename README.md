[![Build Status](https://travis-ci.org/kaguna/Yummy-Recipes.svg?branch=develop)](https://travis-ci.org/kaguna/Yummy-Recipes)
[![Coverage Status](https://coveralls.io/repos/github/kaguna/Yummy-Recipes/badge.svg?branch=develop)](https://coveralls.io/github/kaguna/Yummy-Recipes?branch=develop)
# Yummy-Recipes

Yummy-Recipes is an app that manages users recipes. User can create an account. Using the credentials, the user can login to access the dashboard where registration of the recipe categories take place.
All operations on the category are displayed. Click on the specific category and create a recipe for the category. All the operations on the recipe are displayed.
# Contains

The application contains the user interfaces for the Yummy-Recipes which are contained in the designs directory,

UML diagrams for the Project

The falsk application for Yummy-Recipes contained in the app directory

# Prerequisites

python 3.6 or a later python version is required to run this app.

# Installing
clone the repository

FOR HTTPS
https://github.com/kaguna/Yummy-Recipes

FOR SSH

git@github.com:kaguna/Yummy-Recipes.git

# Change Directory into the project folder

$ cd Yummy-Recipes

# Create a virtual environment with Python 3.6

$ virtualenv --python=python3.6 yourenvname

# Activate the virtual environment you have just created

$ source yourenvname/bin/activate

# Install the application's dependencies from requirements.txt to the virtual environment

$ (yourenvname) pip install -r requirements.txt

# Set up Unit Test Environment

run the following command to install nose unit testing environment:

$ (yourenvname) pip install nose2

This will enable you to run sngle file tests like.

$ (yourenvname) nose2 -v

# Running the program

Run the program by typing the command in your terminal :

$  (yourenvname) python run.py
you can now use the application.