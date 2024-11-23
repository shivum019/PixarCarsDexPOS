# BallsDex Discord Bot - Privacy policy

The following document explains what data is collected by BallsDex.

### Glossary

- "Application" or "Discord application" refers to the Discord bot user, its associated owners and the servers is has
- "Data" refers to data stored by an individual instance, including personal data
- "Bot" or "instance" refers to the copy of the code running the Discord application, with its own data
- "Collectible" refers to any object that is meant to be collected, such as countryballs or other future means like virtual currency
- "Application owners" refers to the owners of the Discord application, meaning the one with any form of access to the application's authentication method and data belonging to the instance. This is usually referred to as the "Ballsdex core team" or "Ballsdex team".
- "BallsDex moderation team" or "moderation team" refers to the owners of the Discord application and the users they may chose to be part of the moderation team. You may find a list of these users on the [Discord server](https://discord.gg/HmSMT4WKKV).

## Open source

The code of BallsDex is open source under the MIT licence and available at https://github.com/laggron42/BallsDex-DiscordBot. A copy of the licence can be found below.

<details>
  <summary>The MIT licence</summary>

  > Permission is hereby granted, free of charge, to any person obtaining a copy
  > of this software and associated documentation files (the "Software"), to deal
  > in the Software without restriction, including without limitation the rights
  > to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  > copies of the Software, and to permit persons to whom the Software is
  > furnished to do so, subject to the following conditions:

  > The above copyright notice and this permission notice shall be included in all
  > copies or substantial portions of the Software.

  > THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  > IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  > FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  > AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  > LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  > OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
  > SOFTWARE.

</details>

You may check the source code and see how the data is managed, in addition to the following policy.

## What data is collected

BallsDex collects the following data from Discord:

- User IDs, this is used to identify you inside our database
- Server (or guild) IDs, this is used to store settings necessary to the bot's operation
- Channel IDs, this is used to know in which channel should the collectibles spawn

In addition, the following data proper to BallsDex is created and used:

- The list of collectibles owned by a user of the service
- A history of trades done on collectibles, including the users that once owned the said collectible but do not anymore
- Various settings configured by an individual user or the server, such as player policies or spawn silent option

The bot has access to the content of messages but is used solely for the purpose of anti-cheat and the said content is not stored longer than necessary for the analysis (under one second). Message content is never cached or stored, and cannot be accessed by the administrators to read your messages.

## How the data is stored

All persistent data is stored on a PostgreSQL server, running on a server hosted by Hetzner.

Interaction between the bot and the database server is exclusively local using [Tortoise ORM](https://github.com/tortoise/tortoise-orm).

## Access to the data

The only persons allowed to access the data are the application owners.

Any application owner may interact with the bot and the administrator interface.

The BallsDex moderation teams do not have access to the data.

The data may never be made available to the public, and its access must be secured accordingly.

## Your rights

You may request a copy or the delection of your personal data held by the application by contacting the application owners. The recommended way is sending an email to "contact (at) ballsdex (dot) com". You may find other means of contact [here](https://gist.github.com/laggron42/52ae099c55c6ee1320a260b0a3ecac4e#contact).

----

Last updated 23rd November 2024
