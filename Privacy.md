PixarCarsDex Discord Bot - Privacy policy
The following document explains what data is collected by BallsDex.

Glossary
"Application" or "Discord application" refers to the Discord bot user, its associated owners and the servers is has
"Data" refers to data stored by an individual instance, including personal data
"Bot" or "instance" refers to the copy of the code running the Discord application, with its own data
"Collectible" refers to any object that is meant to be collected, such as cars cards or other future means like virtual currency
"Application owners" refers to the owners of the Discord application, meaning the one with any form of access to the application's authentication method and data belonging to the instance. This is usually referred to as the "PixarCarsdex core team" or "PixarCarsdex team".
"PixarCarsDex moderation team" or "moderation team" refers to the owners of the Discord application and the users they may chose to be part of the moderation team. You may find a list of these users on the Discord server.
Open source

The MIT licence
You may check the source code and see how the data is managed, in addition to the following policy.

What data is collected
PixarCarsDex collects the following data from Discord:

User IDs, this is used to identify you inside our database
Server (or guild) IDs, this is used to store settings necessary to the bot's operation
Channel IDs, this is used to know in which channel should the collectibles spawn
In addition, the following data proper to BallsDex is created and used:

The list of collectibles owned by a user of the service
A history of trades done on collectibles, including the users that once owned the said collectible but do not anymore
Various settings configured by an individual user or the server, such as player policies or spawn silent option
The bot has access to the content of messages but is used solely for the purpose of anti-cheat and the said content is not stored longer than necessary for the analysis (under one second). Message content is never cached or stored, and cannot be accessed by the administrators to read your messages.

How the data is stored
All persistent data is stored on a PostgreSQL server, running on a server hosted by Hetzner.

Interaction between the bot and the database server is exclusively local using Tortoise ORM.

Access to the data
The only people allowed to access the data are the application owners.

Any application owner may interact with the bot and the administrator interface.

The PixarCarsDex moderation teams do not have access to the data.

The data may never be made available to the public, and its access must be secured accordingly.

Your rights
You may request a copy or the deletion of your personal data held by the application by contacting the application owners. The recommended way is opening a ticket in PixarCarsDex server. You may find other means of contact here.

Extra clause: until April 2nd, midnight UTC
For a limited-time events, PixarCarsdex may read the voice messages in the following conditions

The user accepted the extra clause via /player consent
The message is replying to the bot with a spawned collectible
The user is not blacklisted
The message is less than 5 seconds long If all the conditions above are true, the message will be uploaded to Google API for text recognition. The data is not saved by PixarCarsdex or Google afterwards.
You may read more about Google's usage of the data. PixarCarSDEX DID NOT OPT INTO LOGGING.
https://cloud.google.com/speech-to-text/docs/data-usage-faq
