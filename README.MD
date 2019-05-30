# Flask Upload Image
[![Build Status](https://travis-ci.org/kolawolebalogun/flask_upload_image.svg?branch=master)](https://travis-ci.org/kolawolebalogun/flask_upload_image)

A very simple Flask app which accepts a photo upload via a form, and then displays that photo back to the user, without saving the uploaded file, simply sends it back as a response.

## Requirement

Flask Upload Image has been tested in the following environments

* Python (3.6)

## Installation

First you create a virtual environment:

Start from outside of project root run: 

    virtualenv -p python3.6 flask_upload_image
    cd flask_upload_image
    source bin/activate
    pip install -r requirements.txt
    export FLASK_APP=app.py
    flask run


Flask Docs: 
    http://flask.pocoo.org/docs/1.0/


