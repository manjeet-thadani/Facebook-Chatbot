# Facebook Chatbot using DialogFlow
This project is an simple example of how to create Facebook Chatbot using Dialogflow.
The Dialogflow Facebook integration allows you to easily create a Facebook Messenger bot with natural language understanding, based on the Dialogflow technology.

## Installation

##### Dependencies
1. Install fbchat
```
    pip install fbchat
```

2. Install apiai
```
    pip install apiai
```

## Usage
1. Download above python repository. 

2. Create your [DialogFlow Project](https://dialogflow.com/)

3. Put your credentials in app.py
```
		self.CLIENT_ACCESS_TOKEN = "<your client access token>"
```
```
		# Create an object of our class, enter your email and password for facebook.
    client = Jarvis("<your fb email address>", "<your fb password>")
```
4. Run script
```
		python app.py
```

