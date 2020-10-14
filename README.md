# snpashotalyzer3000

Demo project to manage AWS EC2 instance snapshots

## About

THis project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty ises the configuration file created by the AWS cli e.g.

`aws configure --profile shotty`

## Running

`pipenv run "python shotty/shotty.py <command> <--project=PROJECT>"`

*command* is list, start or stop
*project* is optional
