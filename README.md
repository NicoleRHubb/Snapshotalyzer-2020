# Snapshotalyzer-2020
Demo project to manage EC2 instance snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance spanshots.

## Configuring

shotty uses the configuration file created by the AWS cli. e.g.

`aws configure --profile shotty <command> <--project=PROJECT>`

*command* is list, start, or stop
*project* is optional

## Running

`python3 shotty/shotty.py`
