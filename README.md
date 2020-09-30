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

License

Copyright (c) 2019 Rafael Branquinho

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
