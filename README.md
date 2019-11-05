# Rasa-chatBot
# Rasa Install guid
```
$ sudo apt update
$ sudo apt install python3-dev python3-pip
$ python3 -m venv --system-site-packages ./bot
$ source ./bot/bin/activate
$ pip install rasa-x --extra-index-url https://pypi.rasa.com/simple
```
```
pip uninstall numpy 
pip install numpy==1.16.4

pip uninstall rasa
pip install rasa==1.3.3
```
# Good Tutorial
https://www.youtube.com/watch?v=Xios0aqEVlc


https://rasa.com/docs/rasa-x/api/rasa-x-http-api/


https://medium.com/@itsromiljain/build-a-conversational-chatbot-with-rasa-stack-and-python-rasa-nlu-b79dfbe59491

https://medium.com/@itsromiljain/build-a-conversational-chatbot-with-rasa-stack-and-python-rasa-core-41b9c38c26b

https://www.analyticsvidhya.com/blog/2019/04/learn-build-chatbot-rasa-nlp-ipl/

https://towardsdatascience.com/building-a-conversational-chatbot-for-slack-using-rasa-and-python-part-1-bca5cc75d32f

https://towardsdatascience.com/a-beginners-guide-to-rasa-nlu-for-intent-classification-and-named-entity-recognition-a4f0f76b2a96

https://chatbotslife.com/how-you-can-build-your-first-chatbot-using-rasa-in-under-15-minutes-ce557ea52f2f

https://medium.com/@itsromiljain/3-deploy-your-chatbot-on-slack-1a0e8390f66b

https://itnext.io/building-a-chatbot-with-rasa-9c3f3c6ad64d

https://www.youtube.com/watch?v=seBN1gMJN0U

# it's importent
https://www.youtube.com/watch?v=szZJ0q8Yx7I

https://github.com/RasaHQ/medicare_locator

```
git clone https://github.com/RasaHQ/medicare_locator.git
cd medicare_locator

pip3 install -r requirements.txt

python3 -m spacy download en

make train-core
make train-nlu
make action-server

make cmdline

make interactive

```
https://blog.rasa.com/conversational-ai-your-guide-to-five-levels-of-ai-assistants-in-enterprise/

https://blog.rasa.com/tag/tutorials/

https://github.com/RasaHQ/rasa

https://www.youtube.com/watch?time_continue=1179&v=VXvWdrr2yw8
