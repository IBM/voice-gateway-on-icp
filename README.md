# Automating Call Centers with Voice Gateway on IBM Cloud Private

This code pattern is a Voice Gateway application that enables companies to automate their call centers using Watson Assistant, Text to Speech, and Speech to Text, without having to orchestrate between all the different services yourself; the Voice Gateway will do that for you.

When the reader has completed this Code Pattern, they will understand how to:

* Deploy the Voice Gateway on an IBM Cloud Private Instance
* Connect the Voice Gateway to Twilio via the SIP communication protocol
* Use a Service Orchestration Engine with the Voice Gateway

## Flow

1. Setup the Watson Assistant, Text to Speech, and Speech to Text services on the public cloud.
2. Import the conversation flow, intents, and entities, into the Assistant service.
3. Deploy the Voice Gateway on IBM Cloud Private.
4. Setup Voice Gateway with Twilio.
5. Setup the Service Orchestration Engine (SOE).
6. Connect the Voice Gateway with the SOE.
5. Call the Twilio phone number

TODO: Flow diagram

## Included components

* [IBM Cloud Private](https://www.ibm.com/cloud/private): An on-prem version of IBM Cloud to store your sensitive data and applications.
* [IBM Voice Gateway](https://www.ibm.com/support/knowledgecenter/en/SS4U29/welcome_voicegateway.html): A service that enables you to build apps that leverage Assistant, Text to Speech, and Speech to Text, without having to tie them all in manually.
* [Watson Assistant](https://www.ibm.com/watson/developercloud/conversation.html): Create a chatbot with a program that conducts a conversation via auditory or textual methods.
* [Watson Text to Speech](https://www.ibm.com/watson/developercloud/text-to-speech.html): Converts written text into natural sounding audio in a variety of languages and voices.
* [Watson Speech to Text](https://www.ibm.com/watson/developercloud/speech-to-text.html): A service that converts human voice into written text.
* [Twilio](https://console.ng.bluemix.net/catalog/services/twilio): Integrate voice, messaging, and VoIP into your web and mobile apps.
* [Flask](http://flask.pocoo.org/): is a micro web framework.

TODO: add links.

## Featured Technologies

* [Artificial Intelligence](https://medium.com/ibm-data-science-experience): Artificial intelligence can be applied to disparate solution spaces to deliver disruptive technologies.
* [Python](https://www.python.org/): Python is a programming language that lets you work more quickly and integrate your systems more effectively.

## Prerequisites

TODO: Prerequisites

# Steps

TODO: Steps
