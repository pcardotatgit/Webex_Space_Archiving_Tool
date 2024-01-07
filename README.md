# Webex_Space_Archiving_Tool

In the context of intensively using Webex for sharing informations, or as a alerting system it might be interesting to think about saving conversation stored into Webex Rooms or space.

This is the purpose of the code shared here.

This project already exists, just go to the author github and install the code into your machine.

[Webex Space Archiver](https://github.com/DJF3/Webex-Message-space-archiver)

The code work instantly once you configure the initialisation file. You have to indicate the Room ID of the webex room you want to backup and your Webex Token. You can customize additional parameters as well.

You must belong to the webex room you want to backup.

The result of the code is 3 things :

- First an html page which contains every messages displayed into a nice looking like conversations. And statistics
- Second a Text file which contains these same conversations into a text format
- A third The raw JSON result from Webex

The JSON file could be handy to use for additionnal purpose like storing the result into a database and doing datamining into it.

This script PLUS additionnal python searching function which are very easy to write, is a perfect tool to use to retreive quickly retreive some key conversations among thousand of messages stored long time ago. Retreiving specific conversations on specific topics is actually very difficult to do thru the Webex GUI.

