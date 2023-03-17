
## Initial Setup:
This repo currently contains the starter files.

Clone repo and create a virtual environment
```
$ git clone https://github.com/Soufiane609/ChatBot.git
$ cd chatbot
$ conda create -n envi python=3.6
$ activate envi
```
Install dependencies
```
$ (envi) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (envi) python
>>> import nltk
>>> nltk.download('punkt')
```

Run
```
$ (envi) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (envi) python chat.py
```
and Run
```
$ (envi) python app.py
```





