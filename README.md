# whoscrape

Small Python wrapper to access the WhoIsXMLAPI and save to a MySql database.

## usage

Copy `config.sample.py` to `config.py` and enter values, create a matching database/table in MySql in localhost.

Create a new line separated file in the root directory called `domains`. These are the domains to query and save.

## database

Currently you need to manually create a database table with the following structures `domain`, `email`, and `registrar` of type MediumText.


## requirements

- Python3  
- MySql Connector 


## license

MIT