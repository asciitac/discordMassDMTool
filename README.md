<a href="https://fontmeme.com/discord-logo-font/"><img src="https://fontmeme.com/permalink/200928/622e69213a6b38cfe493fd05f45f66e6.png" alt="discord-logo-font" border="0"></a>

<a href="https://fontmeme.com/discord-logo-font/"><img src="https://fontmeme.com/permalink/200928/48d6f42dbe9624198e085a6b8876b534.png" alt="discord-logo-font" border="0"></a>

[![Discord Server Badge](https://img.shields.io/discord/745447009242316860?color=7289DA&label=Discord%20Server&logo=discord&logoColor=white&style=flat-square)](https://discord.gg/GuBufUE)![Programming Language](https://img.shields.io/badge/-Java-orange?style=flat-square&logo=java)

Discord Mass DM Tool is a Discord Bot Module written in Java using the Javacord API that allows inexperienced developers to send direct messages to everyone in a given server with said bot. It takes up to 4 variables, one of which can be left blank. For other projects, see [here](https://github.com/asciitac)

# Setup
Go to ``/massDm/src/main/java/configuration.java`` and set the given variables to your choosing. 

``String`` ``token`` is your Discord Bot Token. This should be kept secret and can alternatively be an environment variable. You should not share this with anyone, as it gives them complete access to your Discord Account! You can get your bot token from ``https://discord.com/developers/applications/<YOUR PROJECT ID HERE>/bot``.

``String`` ``serverID`` is the server with the members to massDM.

``String`` ``whitelist`` is a ``String`` turned ``Array`` which contains users who should not be DMed.

``String`` ``message`` is the message to send.
