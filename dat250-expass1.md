# Heroku installation process


## Technical problems that you encountered during installation of the software development environment and how you have solved them

I had already installed git and intellij, so there were no additional steps needed and hence no technical problems with this part of the installation process.

## How you have validated (checked) that the software development environment is working

I have checked this by checking that the Java version is recent and that the Java IDE is capable of running a simple "hello world" application.

## Technical problems encountered with the Heroku platform and how you solved them

As I'm running a Linux distro based on debian 11, there were specific steps for this platform that I could discover by searching on the web. I first tried to install heroku using apt-get and curl, but I encountered some errors during the installation process. To properly install Heroku I therefore went the route of installing nodejs and npm (node packet manager), and then I installed Heroku using npm, which seemed to work. However, when trying to run Postgresql, I encountered an error about the username of my computer not existing in Postgresql. I tried to look into this by searching the web and asking the TA, and I don't know if this will be a problem going further.

## Any pending issues with this assignment which you did not manage to solve

Apart from the possible technical issues with the database program described in the previous question, there didn't seem to be any further pending issues. 

## Link to the app:

*https://guarded-chamber-11811.herokuapp.com/*
