# globalChat for TeamSpeak 3
![K-Scripts](https://k-scripts.eu/assets/img/logo.png)

globalChat is bot for TeamSpeak 3.
Chat with the whole server in one window!
  
  - [Informations](#informations)
  - [Installation](#installation)
  - [Commands](#commands)
  - [License](#license)

### It's as simple as can be
  - Install [php5]
  - Edit configuration file
  - Upload files to your server
  - Run it!

## Informations
- Application is free
- Application checks what the user wants to write and automatically removes entries that are vulgar and advertise other services
- The chat automatically ignores the people who are afk

## Installation
Fancy requires [php] 5.4+ and screen [Install instructions.]

Install php5 and screen
```sh
$ sudo apt-get install php5
$ sudo apt-get install screen
```
Edit configuration file (default: config/config.yml)
```yaml
connection:
    ip: 127.0.0.1
    server_port: 9987
    query_port: 10011
    login: serveradmin
    password: Z+67aUoi
[...]
```
## Commands
Upload files to your server

Install the dependencies and start the bot.

```sh
$ cd globalChat
$ php globalChat start
```

Application commands:

```sh
$ !unsub - Turn off chat (When you change your mind, you must contact the administrator)
$ !ban - Banned user permanently (Usage: !ban 13. 13 is clid)
$ !unban - Delete ban and add user to chat (Usage: !unban 15. 15 is client database id)
```

## License
GPL-3.0
You can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

