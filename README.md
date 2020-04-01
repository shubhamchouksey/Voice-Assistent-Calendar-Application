# VOCAL (Voice Assistant Calendar Application)

## Problem Statement: 

This VOCAL bot is a demonstration of how we can use google voice ecosystem to do automation on Google Calendar API. Functionality includes add, remove, move appointments, summarize calendar and check availability.

## Objective and Scope:

**Objective:** To automate the Business meeting and appointments through voice command so that it does not require separate resource to work on it, usually takes less time as compare to fill manually just required your speech and work done simple. 

**Scope:** This can be integrated to your organization mail boxes so that meeting will be scheduled on time and just require few spoken sentence to be done your job. It will save lots of money, time, resources of your organization by automating business meetings.

## Methodology (Hardware & Software Used):

**Hardware:** Google home mini, laptop/PC.    
**Software:** Google calendar API, LUIS (language Understanding Interface System) framework, Microsoft bot framework sdk, nodejs for backend, Azure for deployment, ngrok to allow our bot accessible on internet, 3rd party API to connect Google Home to our bot. 

## How it is going to be useful:
![](/Images/tech_design_architecture.png)

## Getting Started
These instructions will get you a copy of the project up and running on your local machine. You will need to make sure you create a .env file which has your Bot Id, Bot Password, LUIS app id and LUIS subscription key.

### Installing and Running
Easy. Peasy.

```
npm install
npm start
```

By default, the bot will run on port 3978. Download the [Bot Framework Emulator](https://docs.microsoft.com/en-us/bot-framework/debug-bots-emulator) to test locally.
