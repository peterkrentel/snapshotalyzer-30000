# snapshotalyzer-30000

Demo projectg to manange AWS EC@ instance snapshots

## About
This project is a demo, amnd uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

ahotty uses the configuration file created by the AWs cli. e.g.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <subcommand>
<--project=PROJECT>`

*command* is instances, volumes, or snapshots
*subcommand* -depends on command
*project* is optional