# DID-Creation Tool

## Info
This tool can run on either Windows x64 or Linux x64 Systems and requires the Indy SDK to be installed.

## Preparation
1. Clone Repo

2. Install indy-sdk on your system:
https://github.com/hyperledger/indy-sdk#installing-the-sdk

3. Start Tool

### OR
Use [Dockerfile](./Docker/Dockerfile):
1. docker build -t didcreation .

2. docker run -it didcreation ./didcreation/Linux_x64/DIDCreation

## Create a DID
To create a DID simply start the tool and enter your seed.

All information will be on your local machine only.
