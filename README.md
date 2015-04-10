# one-0x001

# SDE-UI

## Prerequisites:
1. Java
2. Mozilla FireFox

## Before Start
1.
Start Selenium Server located in: ./selenium-server/:
java -jar selenium-server-standalone-2.45.0.jar

2.
Update configuration file.
./src/ui/__Config.php

*LOCAL_URL* - is the URL of your local instance of SDE application
(local copy of https://secure.shootdotedit.com/ application).

*DB_XXXX* - parameters of your local database

## Usage
Registration of new user:
* ./src/ui/_RegisterAdmin.php
* ./src/ui/_RegisterClient.php
* ./src/ui/_RegisterEditor.php
The scripts will display in console ID and STUDIO of newly registered users.

If you put new values of ID and STUDIO in configuration (./src/ui/__Config.php),
you cold use scripts for fast login:
* ./src/ui/_LoginAdmin.php
* ./src/ui/_LoginClient.php
* ./src/ui/_LoginEditor.php

More complicated examples:
* ./src/ui/_ClientRegisterPrefColorJob.php
* ./src/ui/_Test735.php [*Make sure Client and Admin are registered*]
