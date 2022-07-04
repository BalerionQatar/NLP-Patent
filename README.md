# NLP Engine for Google Patents

## Introduction

This project involves a Google Patent PDF processor. The repository consists of all the code required to run the web application. You can use the pdf files available in the dataset to upload the pdf files, and you'd be able to see the parsed results. The NLP engine recognizes the variables and values, and it is also capable of recognizing variances between two patent pdf files, when it comes to their variables and the values. 

## Pre-requisites to run the project

#Install the project files, perferably ensure the project folder is on your desktop

Then, run the following command on your terminal:
```bash

cd Desktop
```

To run the virtual environment run this command on your terminal:
```bash
source nlp-server/server/venv/bin/activate
```

Now run the following commands to download the libraries, make sure you're on Desktop:
```
cd Desktop
```
``` bash
arch -arm64 brew install tesseract

```
``` bash
arch -arm64 brew install tesseract

```

``` bash
pip3 install pytesseract
```

``` bash
pip install pdf2image   
```
``` bash
pip3 install pathlib
```
``` bash
pip install flask_cors   
```
``` bash
pip install spacypdfreader  
```
``` bash
pip install -U pip setuptools wheel
```
``` bash
pip install -U spacy
```
``` bash
python -m spacy download en_core_web_sm
```
``` bash
pip install pillow
```
``` bash
npm install axios
```

# Now that's finally out of the way, let's run the project!
# Run the following commands to run the web application:

``` bash
cd Desktop
```
``` bash
cd nlp-server/server/venv
```
``` bash
python3 server.py
```
# The backend is now running! Now for the frontend: 
``` bash
cd ~/Desktop/nlp-server/aptive-react 
```
``` bash
npm start
```
# The web application should be up and running!
# Now just upload the two google patent pdfs you wish to compare


