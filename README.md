# PhoneGSM
For some projects, it is useful to have access to cellular communications. Perhaps you are building a home automation system, and would like to send a text message to turn of the lights. Or, perhaps you wish to make a phone call to a central computer or server, and then implement Natural Language Processing thereafter to fullfil your request.

Services like PubNub and Twilio exist, and provide APIs, for this very purpose. But in a world that seems to be leaning toward open source software more than ever before, having to pay for such a service does not stay true to the mindset of, and is not always practical for, the common hobyist who wants to contribute his/her work to the public domain. 

Indeed, we have a few options. You could pay for such a service, you could purchase a GSM Module, or shield (for an Arduino, Particle board, etc.), or you could use a USB Voice Modem attached to your computer which you would talk to with AT commands.

With a little bit of a "hacker" mindset, however, we can easily turn an old phone into a fully functioning GSM Module equivalent, which will forward calls or text messages to a server of our choosing (I use a RaspberryPi). Once recieved, we can trip a callback function or eventhandler on whatever client is listening. At that point, you can handle the input stream however you like.'


