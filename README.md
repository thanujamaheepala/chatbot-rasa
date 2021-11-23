# chatbot-rasa
A small chatbot using rasa framework.

## Prerequisites
1. Python
2. Rasa - [link](https://rasa.com/docs/rasa/installation/)

## How to run?
1. Open a cmd/terminal in the direcory and run following commands:
  - rasa train
  - rasa run --enable-api --cors "*"
2. Open a cmd/terminal in the direcory and run following command:
  - python -m http.server
3. Go to localhost:8000 from browser and interact with the chatbot.
