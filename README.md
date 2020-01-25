# FTW - Event Planner


## Purpose
FTW is a program to plan events with friends and strangers. Registered users are able to create events. These events can be seen by other users. The creator of the event can make the event visible to everyone or only to friends.
Users can also leave comments on events.


## Setup Guide

### prequisites
* [git](https://git-scm.com/downloads)
* [Node.Js](https://nodejs.org/en/)

### Clone the project to a local directory

1. Open the command line and navigate to the path where the poject should go.
```bash
cd ...
```

2. type the following:

```bash
git clone --recurse-submodules https://github.com/michaelzollweg/SWENGS_FTW.git
cd SWENGS_FTW
```

### Setup the database and start the server
Setup for the Database can be found at the backend repository --> [SWENGS_FTW_Backend](https://github.com/MasterofBisaster/SWENGS_FTW_Backend#setup-guide)


### setup and start the frontend

you can choose one out of two possible ways to setup the frontend:
1. setup using command line
2. setup using IntelliJ IDEA


#### Setup with command line [recommended]
1. open a command line tool and navigate to the project root (cmd executed as Admin is highly recommended)
2. Type the following:
```bash
npm install
npm i -g @angular/cli
ng serve
```
After that the server is startet and you can navigate in a browser of your choice to http://localhost:4200/

#### Setup with IntelliJ IDEA
1. open the backend folder in IntelliJ IDEA and create a new project from existing sources
2. click "run npm install" on the notification on the bottom left to install the dependecies
3. click on "Run Angular CLI Server"

After that the server is startet and you can navigate in a browser of your choice to http://localhost:4200/

## Known Issues

### Issue#1:
Error 403 when trying to register a user.
Solution/Workaround: delete the cookies

## Contributors

* [Lukas Bichler](https://github.com/MasterofBisaster)
* [Tim Braunauer](https://github.com/Urb4nOutl4w)
* [Julian Delazer](https://github.com/Delazerj)
* [Michael Zollweg](https://github.com/michaelzollweg)
