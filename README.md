IRC-logger
==========

This is a simple python application that will log IRC channels. Just add the required channel in options.py and everything else will be taken care of by ```irc-log.py``` What you will have to change is the nickname in irc-log.py. The nickname is found under ```LogBot``` class. Keep this in mind that some channels only allow authenticated users to connect to an irc channel like #python. So you will first need to register your bot with freenode. There are a lot of tutorials on internet to do that. After you get the password just uncomment the lines under ```nickname``` in ```irc-log.py``` and edit them to your liking. And thats it.

###Dependencies:
* twisted

###TODO:
* Add a web interface like botbot.me ? prefferably using Flask

###Author:
* Twisted Matrix
* [M.Yasoob Khalid](yasoob.khld@gmail.com)

###Contribute
* check the readme
* any type of contribution is welcome.