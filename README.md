# Controlling-Raspberry-Pi-using-Alexa
Being able to control Raspberry Pi via voice commands is always amazing. I have demonstrated how you can control your Raspberry Pi using Amazon Alexa. For establishing connection between Raspberry Pi and Alexa, we are going to use certain open-source services and sdk. Logic for controlling Alexa commands and Raspberry Pi will be hosted on local server on Raspberry Pi. As you will require SSL certificates for 'endpoint' in Amazon Alexa, you can use certain open source services to establish tunneling from your Raspberry Pi to Amazon Alexa.

The skill for Alexa will be made using Flask-Ask. For establishing connection we will be using ngrok. ngrok establishes a HTTP tunnel from Raspberry Pi to Alexa. The endpoint url will change every time ngrok is restarted, as an alternative you can use pagekite.

For detailed information visit https://www.hackster.io/nishit-patel/controlling-raspberry-pi-using-alexa-33715b.
