# Dhivehi Reader

Web app to read dhivehi text. Based on machine tts machine learning models available at https://github.com/DhivehiAI/TTS-Demos. Hope the model get furthure improvements.

TODO: Support for scraping dhivehi language websites when url of page is provided.

## Setup
* Install required dependancies `pip install -r requirements.txt`
* Download pre-trained models see https://github.com/DhivehiAI/TTS-Demos for instructions
* Extract and place the model files in ./app/dv_tts/models/


## Run the server
* Run a test server
    python wsgy.py

* Run with gunicorn
    gunicorn wsdy:app

## Deploy to Docker
* TODO

## Deploy to Heroku
Cant deploy to Heroku because the slug size is too big

    heroku login
    heroku create dhivehi-reader
    git push heroku master
    
