![GitHub User's stars](https://img.shields.io/github/stars/RajKKapadia?style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/RajKKapadia?style=for-the-badge)

# Connect OpenAI to Dialogflow CX/ES
Hey everyone, if you are looking for a connection between OpenAI and Dialogflow CX/ES, then read more. You will learn how to connect your existing Dialogflow CX/ES agent to openAI.

# Youtube
I have recorded a quick tutorial on this topic, you can watch it [here]().

### Things you will need
* Dialogflow CX and ES agent
    > some knowledge of Dialogflow CX and ES as well
* OpenAI account and API Key
    > create an account [here](https://openai.com/)
* NGROK for exposing our local server to internet for testing
    > get it from [here](https://ngrok.com/)
* Python as a programing tool
    > install it from [here](https://www.python.org/downloads/)

### How to use it
To replicate the work of this repository and run it locally, you need to follow these steps:
* create a `.env` file inside the root directory, create these environmental variables:
    ```
    OPENAI_API_KEY=YOUR OPENAI API KEY
    ```
* create a virtual environment and activate it before installing the packages
* install all the required dependencies from the `requirements.txt` file
```python
pip install -r requirements.txt
```
* run the server with either of the following commands
```python
python run.py
```
* add the webhook url to Dialogflow
    > CX: YOUR NGROK URL/dialogflow/cx/receiveMessage
    
    > ES: YOUR NGROK URL/dialogflow/es/receiveMessage

# About me
I am `Raj Kapadia`, I am passionate about `AI/ML/DL` and their use in different domains, I also love to build `chatbots` using `Google Dialogflow ES/CX`, I have backend development experience with Python[Flask], and NodeJS[Express] For any work, you can reach out to me at...

* [LinkedIn](https://www.linkedin.com/in/rajkkapadia/)
* [Fiverr](https://www.fiverr.com/rajkkapadia​)
* [Upwork](https://www.upwork.com/freelancers/~0176aeacfcff7f1fc2)
* [Youtube](https://www.youtube.com/channel/UCOT01XvBSj12xQsANtTeAcQ)