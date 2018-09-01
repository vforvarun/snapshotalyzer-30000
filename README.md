# snapshotalyzer-30000
Demo Project to manage AWS EC2 instance snapshots

## About

This is a project demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the configuration file created by the AWS cli.

e.g. `awscli configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <--project=PROJECT>`

*command* is instances, volumes and snapshots
*subcommands* - depends on command
*project* is optional
