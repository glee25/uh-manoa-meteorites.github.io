---
title: UH Manoa Meteorites
---
* [Uh Manoa Meteorites Organization](https://github.com/uh-manoa-meteorites)
* [M1 Project Board](https://github.com/uh-manoa-meteorites/uh-manoa-meteorites.github.io/projects/1?add_cards_query=is%3Aopen)

## Table of contents
* [Overview](#overview)
* [User Guide](#user-guide)
* [Milestones](#milestones)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Deployment](#deployment)
* [Team Members](#team-members)

## Overview


## User Guide

This is a user guide for Volunteer Ally.

### Landing Page

When arriving at the landing page, the user has the option to login to an existing account or create a new one. It also displays general information about the app in case the user is contemplating creating an account.

### Index pages


Login Page:



Signup/Register Page:


### Admin Home Page



### Browse Organizations


### Home page



### Add Event


### Share on Social Media


### Notice for Logging Hours


### Badge System


## Milestones
* In Milestone 1, we will create mockups for the site pages. [M1 Project Board](https://github.com/uh-manoa-meteorites/uh-manoa-meteorites.github.io/projects/1?add_cards_query=is%3Aopen)

## Community Feedback


## Developer Guide

### Installation

First, [install Meteor](https://www.meteor.com/install).

Second, install package...

Then, cd into the app/ directory of your local copy of the repo, and install the required libraries with:

```
$ meteor npm install
```

## Development History


## Running the system

Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file]:

```
$ meteor npm run start
```

The first time you run the app, it will create default users and contacts.

Here is the output:

```
meteor npm run start

> meteor-application-template-react@ start /Users/triciamariereyes/Documents/GitHub/kanak-attack-manoa/app
> meteor --no-release-check --exclude-archs web.browser.legacy,web.cordova --settings ../config/settings.development.json

[[[[[ ~/Documents/GitHub/kanak-attack-manoa/app ]]]]]

=> Started proxy.                             
=> Started MongoDB.                           
data to be populated....
=> Started your app.

=> App running at: http://localhost:3000/
```


### Note regarding "bcrypt warning":

You might also get the following message when you run this application:

```
Note: you are using a pure-JavaScript implementation of bcrypt.
While this implementation will work correctly, it is known to be
approximately three times slower than the native implementation.
In order to use the native implementation instead, run

  meteor npm install --save bcrypt

in the root directory of your application.
```

On some operating systems (particularly Windows), installing bcrypt is much more difficult than implied by the above message. Bcrypt is only used in Meteor for password checking, so the performance implications are negligible until your site has very high traffic. You can safely ignore this warning without any problems during initial stages of development.

### Viewing the running app

If all goes well, the template application will appear at 

### ESLint

You can verify that the code obeys our coding standards by running ESLint over the code in the imports/ directory with:

```
meteor npm run lint
```

## Deployment
A link to our deployed application on Digital Ocean 

## Team Members
* Nicholas Carr
    * [Portfolio](https://nicholasbcarr.github.io/)
* Justin Loi
    * [Portfolio](https://justin-loi.github.io/)
* Gerald Lee
    * [Portfolio](https://glee25.github.io/)

