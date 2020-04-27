# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the configuration file created by the AWS cli. eg.

`aws configure --profile shotty`

## Running

`pipeenv run "python shotty.py <command> <subcommand> <--project=PROJECT>"`

*command* is instances, volumes or snapshots
*subcommand* depends on command: 
    instances: list, start, stop, or snapshot
    volumes, snapshots: list
*project* is optional
