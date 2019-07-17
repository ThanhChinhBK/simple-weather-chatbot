# weather-bot
Rasa NLU/Core Weather Bot

Current configuration supports training, command-line interface and HTTP server API.

## Dependencies

- pip install rasa_nlu
- pip install rasa-core==0.9.6

## Train

First you need to train your bot. You can do that by simply running: *python trainer.py train-all*

This will train both the NLU and Stories using Tensorflow/Keras machine learning.

## Run CMD

To run in command line just call: *python bot.py run*


## 3rd Party Documentations

- Rasa NLU: http://rasa.com/docs/nlu/
- Rasa Core: http://rasa.com/docs/core/
- Weather API: https://pypi.org/project/weather-api/ (Yahoo! Weather)
