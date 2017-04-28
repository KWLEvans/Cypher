# Cypher

Hey, remember the Matrix? That movie was all about code and one character embodied that better than the rest. It's everybody's favorite: Cypher! He's back again to encode your messages using the latest in Shift Cipher technology. Just enter a message, a shift direction, and a shift amount and you'll be a spy in no time!

## Prerequisites

You will need one of the following server management programs properly installed on your computer.

* [MAMP](https://www.mamp.info/en/)
* [WAMP](http://www.wampserver.com/en/)
* [LAMP](https://www.apachefriends.org/index.html)

## Installation

**Step 1**: Clone this repository to your local computer

```console
git clone https://github.com/KWLEvans/Cypher.git
```

**Step 2**: Using your server management software, import the `cipher.sql.zip` file from `/sites/db-backup`

**Step 3**: Create a new user on the database using username: 'ciper' and password: 'ciper'; you can double check in sites/default/settings.php

**Step 4**: Ensure that your web server software's document root is set to the project's root directory and that the MySQL port is set to 8889

**Step 5**: Visit the app at [http://localhost:8889](http://localhost:8889).

## License

MIT License. Copyright 2017 Keith Evans
