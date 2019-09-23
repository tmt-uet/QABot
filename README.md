# QABot
## 1. create evnv
### $ python3 -m venv --system-site-packages ./venv
### $ source ./venv/bin/activate
## 2. install library rasa
### $ pip install rasa-x --extra-index-url https://pypi.rasa.com/simple
### $ pip install rasa_core sklearn_crfsuite spacy rasa_nlu
## 3. run 
### $ python train_nlu.py
### $ python train_dialog.py
### $ python test_dialog.py
